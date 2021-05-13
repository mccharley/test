
name: Manual
on:
   workflow_dispatch:
    inputs:
      name:
        description: 'Person to greet'
        required: true
        default: 'Mona the Octocat'
      home:
        description: 'location'
        required: false
        default: 'The Octoverse'

jobs:
  say_hello:
    runs-on: ubuntu-latest
    env:
      TESTER: "Hello\nWorld!"
    steps:
    - run: |
       echo "name: ${{ github.event.inputs.name }}" 
       echo -e $TESTER
       
       
       name: Manual
on:
   workflow_dispatch:
    inputs:
      name:
        description: 'Person to greet'
        required: true
        default: 'Mona the Octocat'
      home:
        description: 'location'
        required: false
        default: 'The Octoverse'

jobs:
  say_hello:
    runs-on: ubuntu-latest
    env:
      TESTER: "Hello\nWorld!"
    steps:
    - run: |
       echo "name: ${{ github.event.inputs.name }}" 
       echo -e $TESTER
       
       
       
       name: Manual
on:
   workflow_dispatch:
    inputs:
      name:
        description: 'Person to greet'
        required: true
        default: 'Mona the Octocat'
      home:
        description: 'location'
        required: false
        default: 'The Octoverse'

jobs:
  say_hello:
    runs-on: ubuntu-latest
    env:
      TESTER: "Hello\nWorld!"
    steps:
    - run: |
       echo "name: ${{ github.event.inputs.name }}" 
       echo -e $TESTER

