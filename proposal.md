# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: QRMumps.jl

This piece of software is a interface for Julia to allow users to perform QR factorizations using MUMPS. The software can be used to solve symmetric and positive definite linear systems, least-squares problems, and least-norm problems. The main target audience is anyone trying to perform these factorizations on computers with multiple cores.

### Stats

| Description | This package provides a Julia interface to qr_mumps, a software for solving sparse linear systems on multicore computers. qr_mumps implements a direct solution method based on the QR or Cholesky factorization of the input matrix. Therefore, it is suited to solving sparse least-squares problems, to computing the minimum-norm solution of sparse, underdetermined problems and to solving symmetric, positive-definite sparse linear systems. |
|---------|-----------|
| Repository URL |  https://github.com/JuliaSmoothOptimizers/QRMumps.jl  |
| Main/documentation website | https://juliasmoothoptimizers.github.io/QRMumps.jl/stable/ |
| Year project was started |  2015  |
| Number of contributors in the past year | 5 |
| Number of contributors in the lifetime of the project |  7  |
| Number of distinct affiliations | 1 |
| Where do development discussions take place? | GitHub/GitLab issues |
| Typical number of emails/comments per week? | 0-3 |
| Typical number of commits per week? | 0-3 |
| Typical commit size | `git log --shortstat` may be useful |
| How does the project accept contributions? | pull requests |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [ ] I have installed the software
- [ ] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

I did not know what is meant by "number of distinct affiliations" but given the project descriptions I assumed there was only one.
Another concern I have is that I do not really know how active this project is. There have been recent commits, a good number of stars, a good number of contributors but it still does not seem like the most active project out there.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
