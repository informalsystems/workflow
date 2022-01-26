# Roles

Workflow provides a way to construct roles from the bottom-up by understanding
a role as an abstraction over repeated workflows. Any role can be defined by
the pattern of Workflows it is engaged in.

We prefer not to use the term “manager” as it is overloaded and comes with many
connotations. Management is effectively a collection of a number of distinct
concerns which may be better understood as distinct roles. This is the crux of
the [Collaborative Web paper]. Management can be commonly decomposed 
into at least three distinct functions: Product, Project, and People. There is also
a separate function of Technical leadership, which is often confounded
distressingly with these other three functions of management. We define the
following roles for these four functions of managemnent:

| Role  | Concern |  Focus | Project Specific |
|-------|-------------| --- |  --- |  
| Product Owner |  Determine the right thing to build. | Users | Yes | 
| Project Lead | Build the thing on time. | Coordination | Yes | 
| Technical Lead | Build the thing well. | Tech | Yes | 
| Steward | Take care of the people | People |  No |

Notice that the Product, Project, and Technical concerns are project
specific. But the People concern is not - it's a concern for the actual human
beings, not the project they happen to be working on. The 
[Stewardship](/workflow/stewardship.html) section provides more detail.

All of these functions are critical, but it is extremely rare
for a single individual to have the time, let alone the skills, to provide all
of them. Thus, it is recommended that they be understood as distinct roles
and that any individual be responsible for at most two. 

[Collaborative Web paper]: https://galois.com/wp-content/uploads/2016/06/CW-picmet-proceedings.pdf
