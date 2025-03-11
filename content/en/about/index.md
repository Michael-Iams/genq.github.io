---
title: About GenQuery
linkTitle: About
menu: { main: { weight: 10 } }
---

{{% blocks/cover title="About GenQuery" image_anchor="bottom" height="auto" %}}

_A RootsMagic Reporting Engine._

{{% /blocks/cover %}}

{{% blocks/lead %}}

GenQuery is an open-source, third-party RootsMagic reporting engine for use in
the terminal. GenQuery is designed to let you quickly and easily pull structured
genealogy data from your RootsMagic SQLite database. GenQuery is built on top of
[Nushell](https://www.nushell.sh/), a innovative, data-centric shell for
Windows, MacOS and Linux.

{{% /blocks/lead %}}

{{% blocks/section %}}

### What Problem does GenQuery solve?

GenQuery provides three primary new capabilities to the genealogist in search of
a tool to improve the quality and consistency of their genealogy data.

**GenQuery is comprehensive in scope.** RootsMagic 10's Advanced People Search
is powerful yet still quite limited. It only searches Fact/Event records.
GenQuery is designed to report on any type of RootsMagic data, includes sources,
citations, webtags and media.

**GenQuery is infinitely flexible.** If you want to perform additional data
analysis on results of a RootsMagic search, your only option is to save it as a
CSV file and import the data into a tool such as Excel. Nushell's data-centric
programming language can any data transformation you require. Additionally,
GenQuery provides out-of-the box custom command for most of your day-to-day
needs.

**GenQuery improves your workflow.** Have you ever tried to view and edit your
genealogy records while viewing a RootsMagic search results. Keeping both types
windows open and viewable simultaneously is virtually impossible as RootMagic
fights with the user over which window has the focus. GenQuery uses your
Terminal Window.

{{% /blocks/section %}}

{{% blocks/section %}}

### What exactly is Nushell?

Computer systems like Windows and MacOS come with command-line interfaces which
are accessible via a terminal program. The shell is the system layer that
provides this command-line interface. In Windows, the default shell is
Powershell which is the successor to the original Command Prompt. On the Mac,
the default shell is zsh which replaces the older bash shell.

These traditional shells are designed to process the input/output of data as
characters and text. It then is up to the user to write scripts to parse text
into data. While traditional shell scripting powerful, the scripts can be hard
to read and maintain, and are not portable between Windows/MacOS/Linux operating
systems. To better address today's data-centric world, Nushell transforms the
shell paradigm using foundational philosophy centered on processing structured
data.

To help facilitate this, Nushell's scripting language heavily borrow's UNIX's
process piping concept (the " | " symbol), making it a core construct used in
virtually every command. The benefit of this approach is scripts that are both
easy to read and debug while also supporting powerful and efficient data
analytics. Nushell is built using Rust, a modern, fast systems programming
language many view as the eventual replacement for C+ as the most commonly used
systems language. Nushell is also designed to be fully portable across operating
systems, yielding a write-once, run-anywhere capability.

{{% /blocks/section %}}

{{% blocks/section %}}

### How is this different than writing SQLite scripts to access my RootsMagic data?

At its core, GenQuery is running SQLite query scripts. The objective of
GenQuery, and its leveraging of Nushell as a middle-layer above SQL, is to make
writing, maintaining and running these queries easier. Here are the ways
GenQuery simplifies the process.

- No need to learn how to read and write complex SQL queries. Unless you are a
  professional database developer
- No need to learn digest the RootsMagic data model.
- You get to leverage the power of community genealogy cohorts.
- You don't need to worry about your operating system.
- You won't put your data at risk. The danger of accessing RootsMagic data
  directly from the database is that it is allowed by unsupported by the
  RootsMagic company. {{% /blocks/section %}}
