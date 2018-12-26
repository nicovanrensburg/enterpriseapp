## COMPONENTS THAT NEED TO BE DELIVERED ##

### Software Layers
  * UI
  * Mid Tier
  * Data Store
  * Security Layer
  * Logging 

### Infrastructure
  * Cloudformation
  * AWS EC2
  * AWS Lambda
  * AWS Datastore
  * Route 53 / CloudFlare

### CI/CD
  * Concourse
  * Performance testing 
  * GitHub
  
### Productionalization
  * Monitoring
  * Content Delivery Network
  * DDOS mitigation
  
## PROCESS TO CREATE APP ##

### PHASE 1 PLAN SOFTWARE ARCH 
    1. Design the UI
    2. Design the services that will feed the UI
    3. Design the datastore

### PHASE 2. TOOL SELECTION
    1. Pick UI Language / Toolchain
    2. Pick services Language / Toolchain
    3. Pick datastores
    4. Pick infrastructure providers
    5. Pick delivery pipeline components
    6. Pick monitoring toolchain
    
### PHASE 3. SECURITY 
    1. Set up certificates & SSL
    2. Set up data in transit encryption
    3. Set up data at rest encryption
    4. Set up active attack defenses (DDOS)
   
### PHASE 4. MONITORING 
    1. Set up monitoring tools
    2. Design active monitoring for production API's
    3. Design code quality monitoring dashboard
    4. Design infrastructure monitoring dashboard
    5. Ensure central log sink for all events.
  
### PHASE 5. OPTIMIZATION
    1. Identify any performance issues and fix them.
    2. Consider geolocating your services to your customers.
    3. Look at the total cost of operation of your app and see if you can reduce.
