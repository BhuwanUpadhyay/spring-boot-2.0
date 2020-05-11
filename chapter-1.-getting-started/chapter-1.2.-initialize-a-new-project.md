# Chapter - 1.2. Initialize a New Project

The `init` command lets you create a new project by using [start.spring.io](https://start.spring.io/) without leaving the shell, as shown in the following example:

```text
$ spring init --dependencies=web,data-jpa my-project
```

The preceding example creates a `my-project` directory with a Maven-based project that uses `spring-boot-starter-web` and `spring-boot-starter-data-jpa`.

You can list the capabilities of the service by using the `--list` flag, as shown in the following example:

```text
$ spring init --list
```

