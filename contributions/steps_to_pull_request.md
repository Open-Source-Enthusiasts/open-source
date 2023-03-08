### Locate a repo you wish to contribute to
### Fork repo
Look closely at the below images to fork a repo

--Open repo and click on the fork button at the top right corner


![FqofyXhWcAMPGBN](https://user-images.githubusercontent.com/74568105/223595524-f8fe09e0-9d01-4d46-8b2c-56a10acf6e21.jpeg)


--Next, click create fork

![FqofzB7WcAAY1dK](https://user-images.githubusercontent.com/74568105/223595560-dea39a93-71ce-4836-87f5-bddb1c025240.jpeg)

This repo will then be among your list of repositories.

### Clone repo to local system

![FqofzcKWcAUBEHX](https://user-images.githubusercontent.com/74568105/223595607-e5a5e238-ce53-4ead-95f2-6c4d60b2c532.jpeg)

```
1 - Click the code button, a drop-down appears
2 - Click Local
3 - Click HTTPS, you can also use SSH
4 - Copy the link

```
On your local system, navigate to whatever directory you wish to put this cloned repo 

Open this directory in terminal.

Next, clone repo

```
    git clone copied_link
```

The repo should be on your local system now.

### Make contributions and changes.

After making contributions, open your directory in terminal again, Incase you closed the previous one.

### Create a branch 

```
    git checkout -b branch_name
```

- branch_name can be any name

### Add, commit and push changes up

```
git add .
```


```
git commit -m "contribution you made"
```


```
git push --set-upstream origin branch-name
```

### Create Pull Request

Navigate to the forked repo on your GitHub, click on the code tab
You should see something like this 👇

![Fqof1C_WcBcYI5v](https://user-images.githubusercontent.com/74568105/223595445-f4366372-d95e-4bdc-88e3-2dbe55a39934.jpeg)


In the above image, readme2 is the branch_name

Click the COMPARE AND PULL REQUEST BUTTON. You should see something like this 👇

![Fqof1zOWcAEirp7](https://user-images.githubusercontent.com/74568105/223595473-50769ef0-7353-4a5c-bce9-59841a18b4da.jpeg)


Next, comment the changes you made and click the CREATE PULL REQUEST button.
You should get here 👇

![Fqof2T2WYAIqeAM](https://user-images.githubusercontent.com/74568105/223595498-90f794c5-3e31-40ef-a694-2e3145fb7b2a.jpeg)


Congrats 🤝, you have successfully performed a pull request.
