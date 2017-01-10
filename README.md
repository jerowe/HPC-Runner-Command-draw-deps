# HPC::Runner::Command::draw\_deps

Call the hpcrunner.pl draw\_deps command

## Attributes

## Subroutines

### schedule\_jobs

Use Algorithm::Dependency to schedule the jobs

We are overriding this method to produce our dependency trees

# NAME

HPC::Runner::Command::draw\_deps - Draw out the dependency trees of HPC::Runner::Command files

# SYNOPSIS

    use HPC::Runner::Command::draw_deps;

    hpcrunner.pl draw_deps --infile job_file.in

# DESCRIPTION

HPC::Runner::Command::draw\_deps - Draw out the dependency trees of HPC::Runner::Command files using GraphViz2.

# AUTHOR

Jillian Rowe <jillian.e.rowe@gmail.com>

# COPYRIGHT

Copyright 2017- Jillian Rowe

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO
