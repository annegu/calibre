## Steps to Execute Version Increment Github Action

### Step 1
Clone the forked Calibre repository and check out the `release` branch
```
git clone https://github.com/annegu/calibre.git -- branch release
```
The `release` branch has minimum one available release with tag of format `major.minor.patch`.

### Step 2
Push new code to `release` branch. A new tag containing all changes pushes will be made. 

### Step 3
Owner of `release` branch can now create a release using the new tag.