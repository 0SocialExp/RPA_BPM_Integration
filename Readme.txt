## Preparation
1. Install Python 3，install selenium library，install Browser drivers
2. Install Camunda Self-Managed


## Code Description
./RpaTools.py contains functions for controlling TaskList and triggering RPA
./fileTools.py contains functions for reading trigger information files
./IOP_integration contains the files for RPA as a digital employee
./IOP_integration/client.py contains the main logic for Adapter when RPA as a digital employee
./IBP_integration contains the files for RPA as a human assistant
./IBP_integration/service_user.py contains the main logic for Superman Adapter when RPA as a human assistant
./IBP_integration/client_rpa.py contains the main logic for RPA Adapter when RPA as a human assistant 

## Run use case
1. Configure parameters in the code
2. Deploy business processes
3. RPA software listens triggers
4. Run python file