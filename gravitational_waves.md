# Gravitational wave physics jargon

[Go back to index](README.md)

- **Accumulate SNR**: get better SNR by accumulating data over time. Will be the
case for Galactic signals seen by LISA. See **SNR**.

- **BBH**: binary black hole.

- **BHNS**: black hole and neutron star binary system.

- **BNS**: binary neutron star.

- **Characteristic strain**: measure of the strength of a source or of the sensitivity of a
detector, usually noted $h_c(f)$. Cf [Moore et al](http://arxiv.org/abs/1408.0740). 

- **Chirp mass**: characteristic mass scale of binary systems directly measurable from their
GW signal. Defined by

$$
\mathcal{M} = \frac{(m_1 m_2)^{3/5}}{(m_1 + m_2)^{1/5}} = \mu^{3/5} M^{2/5}
$$

where $\mu$ is the reduced mass and $M$ is the total mass. See **dynamical chirp mass**.

- **Dynamical chirp mass**: chirp mass measured from orbital hardening in inspiralling binary,
assuming the energy loss is all due to GW emission.

$$
\mathcal{M} = \frac{c^3}{G} \left( \frac{5}{96} \pi^{-8/3} f_{\text{GW}}^{-11/3} \dot{f}_{\text{GW}} \right)^{3/5}
$$

Notice that this quantity can be negative in case of orbital softening ($\dot{f}_\text{GW} < 0$).

- **GB**: Galactic Binary. White dwarf binary in the Milky Way and satellite galaxies, in the context of LISA.

- **Inspiral**: phase of binary evolution where the system loses orbital energy by emitting
GWs, thereby hardening the orbit.

- **Luminosity distance**: for a binary inspiral,

$$
h_c = 2(4\pi)^2 f_{\text{GW}}^{2/3} \frac{G^{5/3}}{c^4} \frac{\mathcal{M}^{5/3}}{r}
$$

(This is averaged over polarizations and inclinations.) Knowing $h_c$, $f_\text{GW}$, and $\mathcal{M}$,
this equation can be used to measure the distance to the source $r$, in which case this is called
the luminosity distance.

- **MBHB**: Massive Black Hole Binary, $\sim 10^6 M_\odot$.

- **Noise power spectral density**, or **noise PSD**: power spectrum of noise, noted $S_n(f)$.
Measures sensitivity of a detector. Can be two-sided or one-sided. Fully characterizes detector
noise, assuming it is Gaussian. Cf [Moore et al](http://arxiv.org/abs/1408.0740).
See also **root PSD**.

- **Orbital hardening**/**hard orbit**: reduction of major semiaxis of binary system, i.e. the two stars get
closer together.

- **Orbital softening**/**soft orbit**: increase in major semiaxis of binary system, i.e. the two stars get
further apart.

- **PTA**: Pulsar Timing Array.

- **Ringdown**: oscillating GW signal immediately following binary merger.

- **Root PSD**: square-root of noise PSD, noted $\sqrt{S_n(f)}$. Commonly used measure of
detector sensitivity. Units = $\text{Hz}^{-1/2}$.

- **SMBHB**: Super-Massive Black Hole Binary, $\sim 10^9 M_\odot$.

- **Signal-to-Noise Ratio** or **SNR**: measure of GW signal quality, noted $\varrho$.
