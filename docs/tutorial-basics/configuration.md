---
sidebar_position: 2
---

# Configuration

Configuration file is include files and address we need to create hooks and types.

## commandline prompt for configuration


```
npm run swr-codegen --init
```
# Steps

### step1
- What would you like to name the config file ?
    - set a name to config file press enter.
- Would you like to add a script to package.json ?
    - recommend to say yes, create a script in package.json to run easy codegen.
- what is your gateway address ?
    - pass your graphql gateway address full url like ```https://graphqlzero.almansi.me/api```
- What is the glob for your gql files ?
  - write a pattern for your graphql files like ```/**/*.gql```
-  Where would you like to generate the code ?
  - give address to move generated files like ```./src/generated/swr```
- How would you like to address your schema?
 - where is your schema? is file in project or read a url? usualy schema in a url
  - What is the path to your schema file
    - if you select file give file path
  - What is the url of your schema ?
    - if you select url pass schema url
