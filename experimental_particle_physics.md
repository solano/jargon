# Experimental particle physics jargon

[Go back to index](README.md)

- **Acceptance**: fraction of events that are detected. In general, only the product of acceptance
and efficiency is well-defined. While b-tagging efficiency may refer to the fraction of detected
b jets that are b-tagged, b jet acceptance refers to how many b jets are detected in the first place.

- **Acollinearity**: angle between two produced particles in 3D.

- **Acoplanarity**: angle between two produced particles in the transverse plane.

- **b-tagging**, **b-tagged jet**: a jet is b-tagged when we think it comes from a b quark. The main
feature of b jets is that they come from displaced vertices, because the b quark takes time to decay.

- **CLs formalism**: [method](https://www.pp.rhul.ac.uk/~cowan/stat/cls/CLsInfo.pdf) to
produce exclusion limits. For a one-sided right-tail test statistic Q, define

$$
CL_b \equiv \mathbb{P}(Q \le Q_{obs} | \text{background only})
$$

$$
CL_{s+b} \equiv \mathbb{P}(Q \le Q_{obs} | \text{signal+background})
$$

$$
CL_s \equiv \frac{CL_{s+b}}{CL_b}
$$

If $CL_s < \alpha$, we then say that the background-only hypothesis is excluded at the $1-\alpha$
confidence level. To get an exclusion region for, say, $\theta$, vary $\theta$ until $CL_s$ is
exactly $\alpha$.

- **Control region**: region of experimental parameter space that is similar, but not quite equal
to the signal region, commonly used for estimating backgrounds. Example: if the signal region has
two opposite-sign (OS) muons, the control region could be composed of same-sign (SS) muons, or of
a muon and an electron, and so on.

- **Cut**: requirement for the data to be selected. For example: highest $p_T$ jet has to have
$\eta < 2$.

- **Data**: experimental data (not Monte Carlo).

- **Data-driven**: a background or something about it is estimated in a data-driven way if it is not
estimated directly from Monte Carlo, but rather from the data themselves.

- **Displaced vertex**: vertex that is away from the main interaction vertex. Used for b-tagging.

- **Efficiency**: ratio of "successes" over number of "tries". For example, the b-tagging efficiency
is the fraction of b jets that are b-tagged. See also **acceptance**.

- **Exclusion limit**: could be understood as a one-sided confidence interval, i.e. one that places
an upper or lower limit on an observable. In practice is used with the CLs formalism that does not,
strictly speaking, produce confidence intervals.

- **Fiducial region**: geometrical region of detector that where events are considered for analysis.
Events outside the fiducial region (for example for $|\eta|$ too large) are excluded from the data
analysis.

- **Impact**, **pre-fit impact**, **post-fit impact**: a measure of how changing a nuisance parameter
of one standard deviation changes the resulting value of the parameter of interest. Let $\mu$ be
the parameter of interest, $\theta$ be the nuisance parameter under consideration, $\theta_0$ its
expected value, $\Delta \theta_0$ its expected standard deviation, $\hat{\theta}$ its MLE,
$\Delta \hat{\theta}$ the estimator for the standard deviation. The pre-fit impact is defined as
follows: fit the data with all parameters free except $\theta$, fixed at $\theta_0$. Record the
fitted value of $\mu$ as $\mu_0$. Now fit the data again with $\theta$ fixed at
$\theta_0 \pm \Delta \theta_0$, and record the resulting values of $\mu$ as $\mu_\pm$. The pre-fit
impacts are the values of $\mu_+ - \mu_0$ and $\mu_- - \mu_0$. Similarly, for the post-fit impact,
first fit the data with all parameters free except for $\theta$ fixed at $\hat{\theta}$. Record
the resulting value of $\mu$ as $\mu_1$. Then fit the data with $\theta$ fixed at
$\hat{\theta}\pm\Delta\hat{\theta}$, and record the resulting values of $\mu$ as $\mu^{\pm}_1$.
Then the post-fit impacts are the values of $\mu^+_1 - \mu_1$ and $\mu^-_1 - \mu_1$.
Impacts are often presented together with **pulls** in a so-called _pulls and impacts_ plot.

- **Isolated lepton**: the b quark, which is always very boosted in pp colliders due to its low mass,
can decay semileptonically. The resulting leptons are very collinear with the accompanying jet.
Therefore a non-isolated lepton (one that is very collinear with a jet) is probably nonprompt.
See also **non-prompt leptons**.

- **Loose**: a loose particle does not meet all selection criteria for its species. For example,
you may consider that only electrons with $|\eta| \le 2.0$ are to be considered in your analysis, in
which case an electron that meets all other criteria for electrons but has $|\eta| > 2.0$ is a
loose electron. Loose particles are used as control regions. See **tight**.

- **Missing transverse energy**: weakly interacting particles like neutrinos or dark matter
candidates do not deposit any energy in the detector. They are only seen as missing transverse energy
in the collision, i.e. a difference in transverse energy before the collision and after the collision.
See also **transverse energy**.

- **Molière radius**: radius of cylinder containing 90% of the energy deposit in a particle shower.

- **Non-prompt leptons**: either fake (misidentified) leptons or genuine leptons that however do
not come from the interaction of interest. For example, a b quark may decay semileptonically.

- **Pileup**, **pile-up**, **PU**: PU 50 means that 50 collisions are recorded at once, while
only one is used for analysis. Large PU complicates reconstructions.

- **Pull**: Let $\theta$ be a nuisance parameter in a statistical analysis. Let $\theta_0$ be its
expected value, $\Delta \theta_0$ be its expected standard deviation, and $\hat{\theta}$ be its
maximum likelihood estimator (from the data). Then the quantity

$$
\frac{\hat{\theta} - \theta_0}{\Delta \theta_0}
$$

is the pull of $\theta$, measuring how much $\theta$ is "pulled away" from its expected value
by the data. A large pull means that the data prefer a very different value than the one
expected a priori.
Pulls are often presented together with **impacts** in a so-called _pulls and impacts_ plot.

- **Reconstructed**, **reconstruction**: some aspect of a particle collision that has been inferred
from data. For example: an electron is reconstructed from data in the tracking system and the EM
calorimeter using the particle-flow algorithm.

- **Scale factor**: normalization factor of a distribution whose shape is known. Example usage: a
data-driven scale factor derived from a control region.

- **Signal over background** or **S/B**: number of signal events over number of background events
in a given signal region.

- **Signal region**: region of experimental parameter space chosen for analysis. The choice of signal
region is a compromise between number of events and S/B. See **control region**.

- **Signal strength** or **signal strength modifier**: noted $\mu$, is the ratio of observed number
of events to predicted number of events from the Standard Model. This is a simple way of quantifying
deviation from the SM, since the expected value of $\mu$ is always 1.

- **Significance**: p-value, expressed in standard deviations away from the mean of a 1-D Gaussian
distribution. A $5\sigma$ significance (threshold for discovery) means a p-value of $3\times 10^{-7}$.

- **Statistics**, as in **accumulate statistics**: (experimental) data.

- **Thrust**, **thrust axis**: the quantity

$$
T = \max_{|n|=1} \left[ \frac{\sum_i |p_i \cdot n|}{\sum_i |p_i|} \right]
$$

is called the [thrust](https://en.wikipedia.org/wiki/Thrust_(particle_physics)), and the axis $n$ that
maximizes this expression is called the thrust axis.

- **Tight**: a particle is considered tight if it meets all selection criteria for its species.
See **loose**.

- **Transverse energy**: in hadron colliders, because the momentum fraction of partons is unknown,
the center-of-mass frame for each collision is boosted in the longitudinal direction with respect
to the lab frame. This means that only transverse momenta, which are unaffected by this boost, can
really be predicted and compared to the data.

- $X_0$: the distance over which a particle shower loses energy by a factor 1/e.

- **Yield** or **data yield**: number of observed events.
