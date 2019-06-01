# AWS DeepRacer Log Analysis

Note this project was cloned and modified from https://github.com/aws-samples/aws-deepracer-workshops/tree/master/log-analysis
1. [Install AWS CLI](https://aws.amazon.com/cli/)
2. [Create a user in IAM with Admin policy](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html)
3. [Configure AWS CLI Credential](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html#cli-quick-configuration)
4. Run the following command in terminal
```bash
git clone https://github.com/MikletNg/aws_deepracer_log_analysis.git
cd aws_deepracer_log_analysis
chmod +x setup.sh
. ./setup.sh
. ./start.sh
```
5. Run the first 4 cells, above 'Load Waypoints'
6. (Optional) Download model from DeepRacer console, upload the CSV file in 'intermediate_checkpoint/{model_name}'
7. Then you can run 'Model CSV Analysis'
8. Don't run 'Download all the checkpoints' and 'Simulation Image Analysis - Probability distribution on decisions (actions)'