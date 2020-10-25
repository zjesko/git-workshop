# Git Workshop OSDG

This is a repository for the git workshop held by OSDG IIIT-H.
The repository has `hacktoberfest` topic added, hence the pull requests will count towards the completion of the challenge

## Contributing

- Fork this repository by going to https://github.com/akshatcx/git-workshop and clicking on `Fork`
- Clone the forked repository
```bash
git clone https://github.com/<your_github_username>/git-workshop
```
- Change directory into the cloned folder
```bash
cd git-workshop
```
- Checkout to a new branch
```bash
git checkout -b <new_branch_name>
```
- Add a file `<your_name>.json` in the `introductions` folder in the following format
```bash
{
	"name": "your name",
	"branch": "your branch",
	"city": "city where you are from",
	"interests": "your interests"
}
```

A sample file `akshat_chhajer.json` has been added for your reference.

- Add the newly created file
```bash
git add .
```
- Commit the added file
```bash
git commit -m "<your commit message>"
```
- Push the code back to your repository
```bash
git push origin <new_branch_name>
```
- Go back to the initial repository https://github.com/akshatcx/git-workshop and open a pull request





