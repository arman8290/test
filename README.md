#### Step:1 Project setup
- You need to clone the git at very first. to clone git use this command `git clone https://github.com/hudacse6/devxhub.git` (this is https link)
- After that you need copy and paste **.env.example** and setup your **.env** file.
- Then you need to **install Composer**. You can download it from this [link](https://getcomposer.org/download/)
- Then you need to run these commands.
```
php artisan key:generate
php artisan migrate
php artisan db:seed (if seeder available)
php artisan serve
```


#### Step:2 Getting name from Trello card.
- You will get access to the Trello board and you will found all the working, In progress tasks there. Mainly you need to take the card name for your branch name.
#### Step:3 Convert Trello name into Branch name
- You need to convert/Generate the Trello name into a branch name. 
- For generating branch name you can use this [link](https://devtools.stackblitz.io/)
- Here is the image as an example where you need to put what. 
![0.png](https://user-images.githubusercontent.com/19493662/116359281-70cf8480-a820-11eb-8623-93e2e28e8572.png)
![1.png](https://i.ibb.co/ZYCQxRM/1.png)

#### Step:4 Create and switched to a new branch
- You got the Branch name, then you need to create and move into a new git branch.
- To create and move you need to use this down command
`git checkout -b welcome-section-dynamic` 
- Here welcome-section-dynamic is use as example.
![2.png](https://i.ibb.co/BjXQRgC/2.png)
- Then you will see that git switched to a new branch.
![3.png](https://i.ibb.co/NtSbGpK/3.png)



#### Step:5 Commit and push updated code into Git.
- After switched to a new branch you need to type `git add .` to add all your updated code into git
![4.png](https://i.ibb.co/yWm6ySb/4.png)
- Then you need to make a commit. In the commit, you need to mention your update.
Here is an example: `git commit -m "devxhub-#173-welcome-section-dynamic:almost done without image delete"`
![5.png](https://i.ibb.co/6tT64Bz/5.png)
If this commits successfully you get that updated information.
Here is an example of terminal output.
![6.png](https://i.ibb.co/NL3Gm7X/6.png)
- After a successful commit you need to push all code into git.
- To push code into git you need to use `git push`. there you will get the upstream link
![7.png](https://i.ibb.co/7CQLC10/7.png)
- And then use upstream link to get git branch link.
Here is an example code: `git push --set-upstream origin welcome-section-dynamic`
- Then you will get the github branch pull link
![8.png](https://i.ibb.co/8NMGPFd/8.png)


#### Step:6 Merge pull request with the default branch
- Then you need to open the github pull link. in the write input box you need to provide the trello card link.
- Then you need to select the labels, And need to click on the create pull request.
![9.png](https://i.ibb.co/fQBxx6Z/9.png)
- And after that You need to click the Merge pull Request.
![10.png](https://i.ibb.co/C1c83Jc/10.png)
- And at last you need to Confirm merge. And then it will confirm the merge. 
![11.png](https://i.ibb.co/ZhDd6gj/11.png)

#### Step:7 Delete last created branch
- After successfully create the pull and merge, Then you can delete the branch.
![12.png](https://i.ibb.co/ZfDfdV5/12.png)
