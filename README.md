# Checking Out

Lets work on our first feature!

First thing we do is to create a feature branch.

But what branch are we on now?

```bash
$ git branch 
  # * master
```

```bash
```

The asterisk tells us what branch we are on, if we had more branches they would be listed on new lines.

Now we can create that new branch.

```bash
$ git checkout -b new_branch
```

This command will move (checkout) to a new branch (-b) called new_branch which is a copy of the current branch we were working on.

We can confirm this by looking at our branches

``` bash 
$ git branch
  # master
  # * new_branch
```

Right, now we can make some changes. We must always be working on a new branch when we make changes to our code.

First change is to 