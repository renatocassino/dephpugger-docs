---
id: symfony
title: Symfony
sidebar_label: Symfony
---

## Using Dephpugger in Symfony Framework 4

Add in root directory the file `.dephpugger.yml` with the content bellow.

```yml
---
server:
  path: ./public/
  port: 8000
  file: index.php
```

Run the commands bellow in different terminal windows (You must run in the root path).

```bash
$ dephpugger server
$ dephpugger debug
```

You don't need use more `php bin/console server:run` to start the server. If you run this command, you won't get the debugger in breakpoints.

Open [http://localhost:8000](http://localhost:8000) and get work!
