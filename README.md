![image](https://github.com/user-attachments/assets/358ae571-9918-4179-ac95-1367753af3a7)

We installed boto3 to get it to work with the aws plugin

`python -m venv venv`
`pip install boto3`
then run we ran `ansible-playbook playbook.yml  --private-key ~/.ssh/aws -vvv`
