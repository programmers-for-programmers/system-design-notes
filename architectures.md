
# Monolithic Architecture

## What is Monolithic Architecture?

A single, unified codebase and deployment unit containing all application functionalities

1. unified codebase
2. single deployment unit

## Monolithic Architecture good choice for

1. Small focused team
2. Simple application with predictable scale
3. Proof of concepts with quick launches
4. Limited microservice expertise
5. Strong consistency requirements
6. benchmark for monlithic achitecture (this have to be tested) - 2000 concurrent users and 500 requests per second

## Benifits for monolithic architecture

1. Simpler to develop - standard approach
2. Easier debugging and testing - Single codebase, direct calls, faster end-to-end tests
3. Straight forward to deploy - Single artifact, less complex deployment process
4. Simplified intial scaling - scaling up , by adding more resources to the server
5. Lower initial operation overhead - few moving parts to manage
6. Performance - no network latency for internal calls

## Challanges and limitation

1. Growing complexity over time - become big ball of mud, hard to understand
2. Slower deployment speeds - Riskier, hard to implement and fear of breaking changes
3. Deployment bottlenecks - Small changes, needs redeploying entire codebase
4. Barrier to new technology changes - difficult to introduce new languages/frameworks
5. Scalability limitations - Cannot scale componenets independenly
6. Reliability issues - bug in one component can bring down the entire system

## Tips

1. Lets start with monolythic (logical grouping)

# Managing Complexities in Architecture

It is easier to over engineer. These principles helps us build smarter systems.

## Design Principles

1. DRY
2. KISS
3. YAGNI

### DRY - Don't Repeat Yourself
1. Every piece of knowledge must have
   - a single unambiguous
   - authoritative representation within a system
2. Avoid duplicate code, configurations or design elements
3. Promotes maintainability
4. Minimizes Complexity
5. Reduces errors

### KISS - Keep it simple stupid

1. Simplicity should be the key goal
2. Avoid unnecessary complexities in design and implementation
3. Simple systems are easlier to understand and maintain

### YAGNI - You Ain't Gonna Need It

1. Don't implement funcationality based on future speculations
2. From the Extreme Programming methodology - the simplest thing that could possibly work
3. Focus on the current concrete requirements
4. Avoid wasted effort on features that may never be used

#### Example - For developing a e-commerce application

KISS - We aim for simple design, which will meet the e-commerce current needs
YAGNI - We won't build features for hypothetical feature scenarios
DRY - We will look for opportunities to avoid redundancy in the e-commerce modules and components



