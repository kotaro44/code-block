# Bitbucket Server

![Bitbucket Server](./product-logo.png){width=300}

---

## How to contribute

See the [contributing guidelines](./CONTRIBUTING.md).

## References

-   [Home](https://hello.atlassian.net/wiki/spaces/BSERV/overview)
-   [BBSDEV (development Jira)](https://bulldog.internal.atlassian.com/projects/BBSDEV/issues/)
-   [BSERV (public Jira)](https://jira.atlassian.com/projects/BSERV/issues/)
-   [Bamboo](https://server-syd-bamboo.internal.atlassian.com/browse/BSERV)
-   [Core Values](https://hello.atlassian.net/wiki/spaces/STASH/pages/129348944/Stash+Core+Development+Values)

## How to build and run tests

Bitbucket Server requires Maven 3.5+ and Java 8.

    mvn clean install

## How to run and debug

-   Use your editor. Setting up Bitbucket Server in IDEA, and debugging it from there, is [well-documented](https://hello.atlassian.net/wiki/spaces/BSERV/pages/240556172/HOWTO+-+Running+Bitbucket+Server+in+IntelliJ+IDEA)
-   Use AMPS -- `mvn bitbucket:run` or `mvn bitbucket:debug` -- from `func-test/browser` or `func-test/rest`
    -   If you've built Bitbucket Server first, `bitbucket:run` or `bitbucket:debug` will use your local webapp