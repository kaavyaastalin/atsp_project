# atsp_project

1. Use the following command to clone this repo as we have submodules. 

`git clone --recurse-submodules https://github.com/shivammutrejarug/atsp_project.git`

2. `cd atsp_project_von`

3. Make sure docker is running on your machine.

4. `./manage build`

5. `./manage start --logs`

At localhost:9000, you can access explorer to view Network information

6. `cd ../atsp_project_aries/demo`

Now we run agents. These are samples. I had to add code to implement schema and code to issue and verify credentials for the acme agent. Faber is the university, thus, can act as UA for us. Acme is the company, which can act as UG for us. Alice is a student at Faber, which can act as the researcher for our use case. 

7. `./run_demo faber`

8. `./run_demo alice`

9. `./run_demo acme`

Follow instructions now. 

Generally, you provide credential from Faber to Alice and then Acme will ask for verification and verification will happen automatically. 

The issuance is static for now. We need to change this. If we change the issuance, we'll have to change the verification as well. 


