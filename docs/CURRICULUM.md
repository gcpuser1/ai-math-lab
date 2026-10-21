# Curriculum and scope

## Outcome

Given a small unfamiliar learning problem, formulate a model, state assumptions, derive essential calculations, check them numerically and defend whether the result is useful.

Core final demonstrations:
- Derive least squares geometrically and through differentiation.
- Derive gradients for linear and logistic regression, checking signs and shapes.
- Explain gradient descent and demonstrate a step size that fails.
- Trace a 2-input, 2-hidden-neuron, 1-output network, including backpropagation.
- Distinguish training fit from evidence of generalisation.
- Transfer a mathematical idea to a new engineering or everyday problem.

We do not claim broad AI expertise, research readiness or completion of university mathematics courses in 100 sessions.

## Time and adaptation

14–18 hours weekly, roughly 200–257 hours over 100 calendar days. Sessions are numbered learning units; extend the calendar if availability or prerequisites require it. Within each 7-session group use five focused sessions, one application/mixed practice session and one review/assessment session. Specific assessment days in the roadmap override this default.

The roadmap is provisional. A failed gate triggers prerequisite repair in the next session. Record the change and move optional topics out; do not quietly mark failed work complete. Protect the core mechanisms before optional breadth.

## Sequence

| Sessions | Focus | Essential content | Applications |
|---|---|---|---|
| 1–12 | Prerequisites | Equations, units, functions, graphs, powers, logs, summations, basic proof and counterexamples | Scaling, latency, growth |
| 13–37 | Linear algebra and geometry | Vectors, dot products, norms, matrices, transformations, linear systems, span, basis, rank, projections, least squares; introductory eigenvectors/SVD | Similarity, fitting, compression |
| 38–59 | Calculus | Limits, derivatives from differences, derivative rules, chain rule, partial derivatives, gradients, directional change, basic integration | Sensitivity, optimisation, densities |
| 60–79 | Probability and statistics | Events, conditional probability, Bayes, independence, random variables, expectation, variance, covariance, distributions, sampling, estimation and uncertainty | Alerts, experiments, model evaluation |
| 80–90 | Learning objectives and numerical behaviour | Loss, likelihood, log loss, gradient descent, scaling, regularisation, numerical stability | Derive and debug training |
| 91–100 | Synthesis | Regression, gradient checks, small neural network and independent defence | Full learning mechanism |

Geometry is introduced with each operation. Probability is reasoning about uncertain outcomes; statistics is inference from limited observations. Optimisation connects calculus and linear algebra to learning.

## Depth priorities

**Core:** algebra/functions/logs; vector and matrix shapes; dot product; linear transformations; rank and redundancy; projections; derivatives and chain rule; gradients; conditional probability; expectation/variance; sampling uncertainty; squared/log losses; gradient descent; elementary regularisation and backpropagation.

**Selected depth:** eigenvectors, SVD and low-rank approximations; Taylor approximation; entropy; Jacobians; conditioning. Aim for interpretation and tiny examples rather than exhaustive technique.

**Optional:** detailed attention derivation, second-order optimisation, formal convergence arguments, extensive matrix decomposition proofs.

**Deferred:** measure theory, advanced real analysis, full multivariable integration/vector calculus, differential equations, broad statistical testing, full transformer training, diffusion, RL and deployment. Revisit after the core gate.

## Recurring application anchors

1. Synthetic incident data: noisy prediction, false alarms, leakage and data shift.
2. Search: dot products, magnitude, normalisation, cosine similarity and feature units.
3. Resource allocation: constraints, gradients and sensitivity.
4. Compression: redundant directions, rank and approximation.
5. Everyday decisions: uncertain evidence, base rates and expected outcomes.

Applications illustrate mathematics; avoid interpreting synthetic data as operational advice.

## Tools

Begin with paper/whiteboard and hand calculations. Later use plots, sliders and small Python/NumPy experiments. Predict the outcome before executing. No dependency scaffold or pre-solved exercises is needed until a lesson requires one.
