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

## Toolset

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

[ci-defn]: http://martinfowler.com/articles/continuousIntegration.html
[cd-defn]: http://docs.aws.amazon.com/codepipeline/latest/userguide/concepts.html#concepts-continuous-delivery-integration
