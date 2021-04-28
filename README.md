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

![0](https://user-images.githubusercontent.com/19493662/116362897-61ead100-a824-11eb-9340-6d9250693751.png)
![1](https://user-images.githubusercontent.com/19493662/116362921-68794880-a824-11eb-8659-33b155062841.png)

#### Step:4 Create and switched to a new branch
- You got the Branch name, then you need to create and move into a new git branch.
- To create and move you need to use this down command
`git checkout -b welcome-section-dynamic` 
- Here welcome-section-dynamic is use as example.


![2](https://user-images.githubusercontent.com/19493662/116362943-6d3dfc80-a824-11eb-9b9e-f65016d2bf4d.PNG)

- Then you will see that git switched to a new branch.


![3](https://user-images.githubusercontent.com/19493662/116362967-74fda100-a824-11eb-836d-1845213f856f.png)




#### Step:5 Commit and push updated code into Git.
- After switched to a new branch you need to type `git add .` to add all your updated code into git

![4](https://user-images.githubusercontent.com/19493662/116362986-7929be80-a824-11eb-9f89-5062fb087f4e.png)

- Then you need to make a commit. In the commit, you need to mention your update.
Here is an example: `git commit -m "devxhub-#173-welcome-section-dynamic:almost done without image delete"`

![5](https://user-images.githubusercontent.com/19493662/116363008-7dee7280-a824-11eb-8a3b-badc594f9a5e.png)

If this commits successfully you get that updated information.
Here is an example of terminal output.

![6](https://user-images.githubusercontent.com/19493662/116363031-82b32680-a824-11eb-969b-c3f9409af92f.png)

- After a successful commit you need to push all code into git.
- To push code into git you need to use `git push`. there you will get the upstream link

![7](https://user-images.githubusercontent.com/19493662/116363044-86df4400-a824-11eb-8b81-1ec4bbba6136.png)

- And then use upstream link to get git branch link.
Here is an example code: `git push --set-upstream origin welcome-section-dynamic`
- Then you will get the github branch pull link

![8](https://user-images.githubusercontent.com/19493662/116363093-952d6000-a824-11eb-9862-4ec45fcf5678.png)



#### Step:6 Merge pull request with the default branch
- Then you need to open the github pull link. in the write input box you need to provide the trello card link.
- Then you need to select the labels, And need to click on the create pull request.

![9](https://user-images.githubusercontent.com/19493662/116363106-99597d80-a824-11eb-8a47-4f71a04b8219.png)

- And after that You need to click the Merge pull Request.

![10](https://user-images.githubusercontent.com/19493662/116363112-9c546e00-a824-11eb-9dfc-94d75d35d953.png)

- And at last you need to Confirm merge. And then it will confirm the merge. 

![11](https://user-images.githubusercontent.com/19493662/116363127-9f4f5e80-a824-11eb-9182-7fce1edc87db.png)


#### Step:7 Delete last created branch
- After successfully create the pull and merge, Then you can delete the branch.

![12](https://user-images.githubusercontent.com/19493662/116363134-a24a4f00-a824-11eb-90e6-3f97c7cfd2f7.png)

