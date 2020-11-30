# 2011_hsma_dqn

Deep Q Networks - using CartPole and a hospital bed simulator.

*01_catpole_basics*: Demo of CartPole

*02_cartpole_ddqn*: Double Deep Q network for CartPole

*03_hospital_ddqn*: Double Deep Q network for staffing of beds ina hospital (SimPy simulation is simpy_envs/env_simple_hospital_bed_1.py)


## Set up environment

To create environment. Navigate to where environment.yml is located and type

`conda env create -f environment.yml`

To activate environment:

`conda activate rl`

To deactivate:

`conda deactivate`

To update environment (from updated yml file):

`conda env update --prefix ./env --file environment.yml  --prune`

To remove:

`conda env remove -n rl`
