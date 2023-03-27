# Performing a release

* Increment the version in `package.json`
* Update to lock file:
  
  ```shell
  npm i
  ```
* Commit the changes
* Create a new tag
* Push changes and tag:
  
  ```shell
  git push
  git push --tags
  ```
* Publish a new package
  
  ```shell
  npx vsce publish 
  ```
