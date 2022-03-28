# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ----- | ------ |
|   Efrain = { username:Cowboys4Life, isActive: True }     |   "Welcome back, Cowboys4Life!"             | 
|   Carla = { username: DallasTX, isActive: False)     |    "Hey DallasTX! Would you like to renew your subscription?"    | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This is checking if an user who is logging in an active user or not, if user is active then user will get message Welcome back, (username).
If user is not active then user will get message asking them if they would like to renew their subscription. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
