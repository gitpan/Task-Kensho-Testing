# NAME

Task::Kensho::Testing - A Glimpse at an Enlightened Perl: Testing

# VERSION

version 0.36

# SYNOPSIS

    > cpanm --interactive Task::Kensho::Testing

# DESCRIPTION

From [http://en.wikipedia.org/wiki/Kensho](http://en.wikipedia.org/wiki/Kensho):

> Kenshō (見性) (C. Wu) is a Japanese term for enlightenment
> experiences - most commonly used within the confines of Zen
> Buddhism - literally meaning "seeing one's nature"\[1\] or "true
> self."\[2\] It generally "refers to the realization of nonduality of
> subject and object."\[3\]

[Task::Kensho](https://metacpan.org/pod/Task::Kensho) is a list of recommended modules
for Enlightened Perl development. CPAN is wonderful, but there are too
many wheels and you have to pick and choose amongst the various
competing technologies.

The plan is for [Task::Kensho](https://metacpan.org/pod/Task::Kensho) to be a rough testing ground for ideas that
go into among other things the Enlightened Perl Organisation Extended
Core (EPO-EC).

The modules that are bundled by [Task::Kensho](https://metacpan.org/pod/Task::Kensho) are broken down into
several categories and are still being considered. They are all taken
from various top 100 most used perl modules lists and from discussions
with various subject matter experts in the Perl Community. That said,
this bundle does _not_ follow the guidelines established for the EPO-EC
for peer review via industry advisers.

Starting in 2011, [Task::Kensho](https://metacpan.org/pod/Task::Kensho) split its sub-groups of modules into
individually-installable tasks.  Each [Task::Kensho](https://metacpan.org/pod/Task::Kensho) sub-task is listed at the
beginning of its section in this documentation.

When installing [Task::Kensho](https://metacpan.org/pod/Task::Kensho) itself, you will be asked to install each
sub-task in turn, or you can install individual tasks separately. These
individual tasks will always install all their modules by default. This
facilitates the ease and simplicity the distribution aims to achieve.

# RECOMMENDED MODULES

## [Task::Kensho::Testing](https://metacpan.org/pod/Task::Kensho::Testing): Testing

### [Devel::Cover](https://metacpan.org/pod/Devel::Cover)

Code coverage metrics for Perl

### [Test::Deep](https://metacpan.org/pod/Test::Deep)

Test deep data structures

### [Test::Fatal](https://metacpan.org/pod/Test::Fatal)

Test exception-based code

### [Test::Memory::Cycle](https://metacpan.org/pod/Test::Memory::Cycle)

Check for memory leaks and circular memory references

### [Test::Most](https://metacpan.org/pod/Test::Most)

Most commonly needed test functions and features.

### [Test::NoWarnings](https://metacpan.org/pod/Test::NoWarnings)

Ensure that no (unexpected) warnings occur during testing

### [Test::Pod](https://metacpan.org/pod/Test::Pod)

Check for POD errors in files

### [Test::Pod::Coverage](https://metacpan.org/pod/Test::Pod::Coverage)

Check for pod coverage in your distribution.

### [Test::Requires](https://metacpan.org/pod/Test::Requires)

Make running a test conditional on a particular module being installed

### [Test::Simple](https://metacpan.org/pod/Test::Simple)

Basic utilities for writing tests.

# INSTALLING

Since version 0.34, [Task::Kensho](https://metacpan.org/pod/Task::Kensho) has made use of the `optional_features` field
in distribution metadata. This allows CPAN clients to interact with you
regarding which modules you wish to install.

The `cpanm` client requires interactive mode to be enabled for this to work:

    cpanm --interactive Task::Kensho::Testing

# BUGS AND LIMITATIONS

This list is by no means comprehensive of the "Good" Modules on CPAN.
Nor is this necessarily the correct path for all developers. Each of
these modules has a perfectly acceptable replacement that may work
better for you. This is however a path to good perl practice, and a
starting place on the road to Enlightened Perl programming.

Please report any bugs or feature requests to
[https://github.com/EnlightenedPerlOrganisation/task-kensho/issues](https://github.com/EnlightenedPerlOrganisation/task-kensho/issues).

# SEE ALSO

[http://www.enlightenedperl.org/](http://www.enlightenedperl.org/),
[Perl::Dist::Strawberry](https://metacpan.org/pod/Perl::Dist::Strawberry)

# AUTHOR

Chris Prather <chris@prather.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2008 by Chris Prather.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
