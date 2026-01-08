# Tasks

Automate blockchain transactions with task groups.

## Task Groups

Tasks are organized into groups. Each group is linked to a wallet group.

### Creating a Task Group

1. Click **New Task Group** in the header
2. Enter a name
3. Select which wallet group to use
4. Click Create

### Viewing Tasks

Click on a task group card to see all tasks inside.

## Adding Tasks

1. Open a task group
2. Click **Add Task**
3. Fill in task configuration:
   - Contract address
   - Function to call
   - Gas settings
   - Any additional parameters
4. Save the task

## Running Tasks

### Single Task
Click the play button on any task to run it individually.

### All Tasks
Click **Execute All** to run every task in the group at once.

## Task Status

| Status | Meaning |
|--------|---------|
| Ready | Task is configured and waiting to run |
| Simulating | Task is being simulated before sending |
| Scheduled | Task is queued to send transaction |
| Failed | An error occurred or transaction failed |
| Cancelled | Task was stopped by user |

## Stopping Tasks

- Click stop on individual tasks
- Or use **Stop All** to cancel everything

Running transactions may still complete on the blockchain.

## Tips

- Test with small amounts first
- Make sure wallets have enough gas
- Double check contract addresses before running
