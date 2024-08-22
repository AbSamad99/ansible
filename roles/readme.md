# Roles

These can be referenced in your main playbook. Each directory in this folder corresponds to a role. Each is a parent directory to the following (In our cases): tasks and files. The tasks sub-directory contains the main.yml file, which contains the list of tasks (Not plays!!) to be performed, hence why it is called a taskbook. The files sub-directory contains all the files that the task might need such as in the case where we are copying the index.html file to the server. 
