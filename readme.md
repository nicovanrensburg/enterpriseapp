## COMPONENTS THAT NEED TO BE DELIVERED ##

-Software Layers
  UI
  Mid Tier
  Data Store
  Security Layer
  Logging 

-Infrastructure
  Cloudformation
  AWS EC2
  AWS Lambda
  AWS Datastore
  Route 53

-CI/CD
  Concourse
  Performance testing 
  GitHub
  
Productionalization
  Monitoring
  Content Delivery Network
  DDOS mitigation
  
## PROCESS TO CREATE APP ##

PHASE 1 PLAN SOFTWARE ARCH
    Step 1. Design the UI
    Step 2. Design the services that will feed the UI
    Step 3. Design the datastore

PHASE 2. TOOL SELECTION
    Step 1. Pick UI Language / Toolchain
    Step 2. Pick services Language / Toolchain
    Step 3. Pick datastores
    Step 4. Pick infrastructure providers
    Step 5. Pick delivery pipeline components
    Step 6. Pick monitoring toolchain
    
PHASE 3. SECURITY 
   Step 1. Set up certificates & SSL
   Step 2. Set up data in transit encryption
   Step 3. Set up data at rest encryption
   Step 4. Set up active attack defenses (DDOS)
   
PHASE 4. MONITORING 
  Step 1. Set up monitoring tools
  Step 2. Design active monitoring for production API's
  Step 3. Design code quality monitoring dashboard
  Step 4. Design infrastructure monitoring dashboard
  Step 5. Ensure central log sink for all events.
  
PHASE 5. OPTIMIZATION
  Step 1. Identify any performance issues and fix them.
  Step 2. Consider geolocating your services to your customers.
  Step 3. Look at the total cost of operation of your app and see if you can reduce.