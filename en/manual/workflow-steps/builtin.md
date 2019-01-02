% Builtin Workflow Steps

### Ansible Module

### Ansible Playbook Inline

### Ansible Playbook

### Global Variable

### Flow Control

### Job State Conditional

To identify the status of another job, exist Job State Conditional, also can identify a condition depending on the job last status.

* **Job Project** - In case a job it in inside on another project can specify here.

* **Job Name** - Job name in format: Group/Name.

* **Job UUID** - Job UUID that can evaluate status or last execution status.

* **Running** - If the job is running (true/false). If select "none select" Job State Conditional doesn't evaluate this.

* **Execution State** - Check the job last state, select "Never" means the job has never executed. Also can use custom status.

* **Condition** - Whether the assertion should match or not.

* **Halt** - Halt if the Condition is not met. If not selected, the workflow execution will continue.

* **Status when Halted** - Use a custom status message when Halted, that's show on Activity panel.

* **Step Label** - A short description of the step.

In all these fields you can use variables as options of type ${option.jobname} or ${option.uuid}.

### Log Data Step

### Refresh Project Nodes

### Data Step
