# `C(I|D)`
## Continuous Integration and Delivery
## Brian Besmanoff
:octocat: @bbesmanoff

---

## Real Talk
This talk contains my own ideas.

*My own meaning it doesn't represent any product/service/company/etc.*

---

## Definitions

---

## Continuous Integration

> Continuous Integration is a software development practice where members of a
> team integrate their work frequently, usually each person integrates at least
> daily

> --[Martin Fowler][ci-defn]


---

## Continuous Delivery

> Continuous delivery is a software development methodology where the release
> process is automated. Every software change is automatically built, tested,
> and deployed to production

> --[AWS CodeDeploy][cd-defn]

---

## Aren't those the same?

---

## Technically no
*best kind of no*

---

## Theory
The theory is that CI just checks your code against everyone elses and the CD
will run a full build/test cycle in addition to a release cycle

---

## Practice
YMMV

---

## How do I get started?

---

## Step 1: Build Process

---

## Step 1: Build Process
* Decide on what is required for a build

```note
Unit tests?  Integration tests?  Linting/style-checking?
```

---

## Step 2: Pick a tool

---

## There are many out there...

* Jenkins
* AWS CodePipeline
* TravisCI
* CircleCI

---

## There are many out there...

* Jenkins
* AWS CodePipeline
* TravisCI
* CircleCI

*mix of "true" ci and "true" cd*

---

## Step 3: Integrate it With Source Control

```note
live demo using example app
```

---

## Step 4: ???

---

## Step 5: :money_with_wings:

---

## Next Steps

---

## Start to integrate, continuously

---

## Start to integrate, continuously
`git rebase origin master`

```note
rebase is not your enemy
```

---

## Rebasing
> Forward-port local commits to the updated upstream head

> [git-rebase(1)][rebase-man]

---

## Rebasing

```
          A---B---C topic
         /
    D---E---F---G master
```

... to ...

```
                  A'--B'--C' topic
                 /
    D---E---F---G master
```

---

## Rebasing

`git push --force origin topic`

---

## Rebasing

`git push --force origin topic`

![Deal with
it](http://i3.kym-cdn.com/entries/icons/original/000/002/686/Deal_with_it_dog_gif.gif)


---

## CircleCI's Got Your Back

---

(demo time)

---

## Why should I use it?

---

## Why should I use it?
* (hopefully apparent)

---

## Why should I use it?
* (hopefully apparent)
* Fast feedback

---

## Question?

[ci-defn]: http://martinfowler.com/articles/continuousIntegration.html
[cd-defn]: http://docs.aws.amazon.com/codepipeline/latest/userguide/concepts.html#concepts-continuous-delivery-integration
[rebase-man]: https://git-scm.com/docs/git-rebase
