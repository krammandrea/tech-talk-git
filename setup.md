
Getting started
==============


Check configuration
---------
Check your configuration
```
git config -l
```

Set your user name and email if not set already
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

Important (optional) tip
------------
- Color is easier to read
```
git config color.ui true
```

Start a repository
------------
```
mkdir targetDirectory
cd targetDirectory
git init
```
or 
```
cd parentOfTargetDirectory
git clone getHttpsCloneUrlFromGithub
```
