# Tag and Version

When I'm writing code, I have some standards for how I did mark versions. 

When I've written test code that apparently works, I call that _alpha_ and have a version number < 1, for example, v0.1.

Once the code is ready to go to other users for testing, I called that _beta_, version number still < 1 , for example, v0.2. .

After that, my first production release is v1.0. After a small edit or fix, this becomes v1.1.

For example

````dos
git tag -a v0.1 -m "Alpha release 1"
````

Typing git tag will show a list of previously used tags.