This is data from the "AInix Kernel Dataset (Archie Release)". The data was exported from https://github.com/AInixProject/AInix 90d23da97e3a which is more nicely formatted for editing as yaml files. However, wanted to make a version that is json to be more compatible with the NLC2CMD challenge (http://nlc2cmd.us-east.mybluemix.net/).

For more context about the dataset see https://apps.cs.utexas.edu/apps/tech-reports/177982
```
@article{gros2019ainix,
  title={AInix: An open platform for natural language interfaces to shell commands},
  author={Gros, David},
  year={2019}
}
```

Note this repo is missing nicely pulled out eval code which parses the examples and compares the AST as was done in AInix. That is still a todo (partly because I want to completely rewrite the parsing code)... Let me know if it would be useful to you and I can revisit it in a quicker solution.
