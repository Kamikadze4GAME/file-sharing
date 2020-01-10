### Information

It is based on [GitHub Page](https://pages.github.com) and has the ability to sort and filter data through the use of [jQuery](https://jquery.com) and [DataTables](https://datatables.net).

#### File sharing & Cloud storage

* [File sharing](https://nafanz.github.io/filesharing.html) - only resources that do not require registration.
* [Cloud storage](https://nafanz.github.io/cloudstorage.html) - only resources with a free tariff unlimited in time of use (not trial).

#### Misc
* [Wishlist](https://nafanz.github.io/wishlist.html) - what I want to find (movies, music).

### Contributions

* Fork this repository

Clicking on the `Fork` button on the top of this page. This will create a copy of this repository in your account.

* Clone the repository

Go to your GitHub account, open the forked repository, click on the `Clone or download` button and then click the copy to clipboard icon. Open a terminal and run the following git command:

`git clone <url repository>`

* Open a project in IDE or text editor

Recommendations: [IntelliJ IDEA Community](https://www.jetbrains.com/idea/), [Visual Studio Code](https://code.visualstudio.com) or [Sublime Text](https://www.sublimetext.com)

* Make changes to the file `cloudstorage.html` or `filesharing.html`, for example:

```
<tr>
    <!-- File sharing -->
    <td>
        <a href="https://1fichier.com">1fichier</a>
    </td>
    <!-- Maximum file size -->
    <td>300 GB</td>
    <!-- Shelf life -->
    <td>15 +</td>
    <!-- Download count -->
    <td>-</td>
    <!-- Language -->
    <td>English</td>
</tr>
```

* Commit the changes and push

`git commit -m "Add <name cloud storage or file sharing>"`

* Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

You will get a notification email once the changes have been merged.

* Synchronize your branch with this repository

Add the url of my repository to the field `upstream <remote url>`:

`git remote add upstream git@github.com:nafanz/nafanz.github.io.git`

Download the latest changes from my repository.

`git fetch upstream`

We are merging a new version of my repository with your master branch.

`git rebase upstream/master`

Pushing these changes to your GitHub repository.

`git push origin master`

* Profit

Keep track of the project and make new changes.

### Contacts

Email `nafanz@mail.ru` or Reddit `u/x4fs1j`
