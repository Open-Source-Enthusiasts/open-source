Locate a repo you wish to contribute to
Fork repo
Look closely at the below images to fork a repo

--Open repo and click on the fork button at the top right corner

[label](https://twitter.com/rivondave/status/1633152771733041154/photo/1)

--Next, click create fork

[label](https://twitter.com/rivondave/status/1633152778976522244/photo/1)

This repo will then be among your list of repositories.

Clone repo to local system

[label](https://twitter.com/rivondave/status/1633152790510858254/photo/1)

1 - Click the code button, a drop-down appears
2 - Click Local
3 - Click HTTPS, you can also use SSH
4 - Copy the link

On your local system, navigate to whatever directory you wish to put this cloned repo, open this directory in terminal.

Next, clone repo

```
    git clone copied_link

```

The repo should be on your local system now.

Make contributions and changes.

Open your directory in terminal again, Incase you closed the previous one.

Create a branch 

```
    git checkout -b branch_name
```

- branch_name can be any name
- perform all git operations stated in this tweet without the brackets

Add our changes 

```
git add .
```

Commit changes 
```
git commit -m "contribution you made"
```

Next we push our changes up 
```
git push --set-upstream origin branch-name
```

Next, navigate to the forked repo on your GitHub, click on the code tab
You should see something like this 👇


/rivondave/status/1633152817815777290/photo/1


In the above image, readme2 is the branch_name

Click the COMPARE AND PULL REQUEST BUTTON. You should see something like this 👇

/rivondave/status/1633152827999547393/photo/1

Next, comment the changes you made and click the CREATE PULL REQUEST button.
You should get here 👇

/rivondave/status/1633152839101870082/photo/1

Congrats 🤝, you have successfully performed a pull request.