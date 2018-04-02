# Python Data Sciences starter kit

## Installation

1. Create a repository on a web hosting for version control or your own server

2. Clone the repository with the name of your project
```
git clone -o boilerplate -b master --single-branch git@github.com:florentpietot/data-sciences-python-starter-kit.git Project
cd Project
```
3. Update LICENSE.md and README.md
4. Setup new origin (change username and project name)
```
git remote add origin git@github.com:username/project.git
git push -u origin master
```

If you want to integrate new changes from starter kit into your project
Warning: this might create merge conflicts
```
git fetch boilerplate
git merge boilerplate/master
```
Otherwise, if you don't intend to get new changes from boilerplate,
just delete the remote
```
git remote rm boilerplate
```

## Usage
* **cache**: cache your features and datasets here
* **input**: place the raw data files here
* **logs**: logging files
* **notebooks**: jupyter notebooks
* **output**: your models predictions
* **plots**: for diagnostics plots
* **tests**: your tests go here

## License
MIT License

Copyright (c) 2017 Florent Piétot

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
