# Community Module Template 
This repository is meant to serve as a general template for how to set up new community knowledge modules. 

## Checklist
### *.LLM
- Copy the `example.llm` file and update the information in the file. This file contains the knowledge that will be accessed by the language model.
- Set the privacy access control for your module. The options are as follows:
```
{
  1: Public read / public write, # Anyone can use the module and contribute to it
  2: Public read / private write, # Anyone can use the module but only invited members can update the information
  3: Private read / private write, # Only invited members can read and update the information
  4: Private read-only  # Only invited members can read and only the module creator can update the information 
}
```

### README
- Copy the `example-README.md` file to include the title of your module. If your repo contains multiple `*.llm` files, create a separate README for each file.
- Edit the information on access control to reflect how edits to the module will be managed. 

