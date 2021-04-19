# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on.  The counterpart to this is **local**, or the mahcine that is being developed on.

Take Github for example.  While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories.  Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositores (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning its your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
