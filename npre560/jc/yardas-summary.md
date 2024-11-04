This paper introduced a time-dependent variant of the fission matrix method for
use in reactor kinetics calculations and dynamics calculations when coupling
with a thermal hydraulics code. The paper's strength is in its novelty, however,
the internal logic, layout of arguments, introduction of mathematical and
physical concepts, and writing style are all weak and detract from the quality.
of the paper. This paper would have been improved by additional proofreading.

The only motivation the paper hints at is development of a transport method that
can take into account moving precursors as would exists in molten salt reactors,
however this is an inference from details given in the conclusion of the paper.
Objectives are clearly defined as 1) development of a new approach to model
time-dependent neutron flux for coupling with thermal hydraulics codes, and 2)
validation of this method via kinetic parameter calculation on benchmark
problems.

The method was at the time of publication nearly 10 years ago, but since then
there have been other efforts at using the fission matrix method for
time-dependent reactor physics calculations. The novelty of the work was not
emphasized by the authors, and there was not really a literature review. In
fact, the introduction of the paper was just a rehash of the abstract!

The method itself is interesting, but I believe it should have been built up
systematically from a discussion of eigenvalue fission matrix methods and
reactor kinetics. The approach taken by the authors in the paper is confusing
and not very extensible. There was no discussion of uncertainty propagation
in the method.

The results presented in the paper support the goals, but I hesitate to say
they support the conclusions. The models used in the results were extremely
simple and only served as a proof-of-concept. It is possible that additional
work performed in the 2017 follow-up paper tackled a more complicated model. As
for extensions, I would be interested in compute-time comparisons between the
method presented and time-dependent monte carlo or detereministic methods.

