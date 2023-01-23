# Project 4: Chronoamperometry and Cyclic Voltammetry
### Tanner Leo, University of Oregon, Electrochemistry Lab, November 28<sup>th</sup>

## 1 Introduction
**Kinetics: Theory and Ligand Contributions**

While thermodynamics dictates the conditions for equilibrium of an electron transfer reaction, the kinetics of the reaction take precedent in governing the various aspects of the electron transfer reaction. The kinetics of electron transfer reactions describe how the system evolves with time as the conditions around the reaction change. Marcus theory presents a practical method for describing electron transfer kinetics from the microscopic level.[<sup>1</sup>](#bard) 

In Marcus theory, the free energy of activation describes the energy required to overcome the activation barrier for an electron transfer step. The magnitude of the activation energy barrier depends on the reorganization energy, &lambda;. Further, the kinetic rate constants for a reaction are exponentially proportional to the reorganization energy. The reorganization energy is often split into the inner and outer reorganization energies, for the active species involved and the solvent, respectively. Equations 1 and 2 below are often used to calculate the inner and outer reorganization energies.

\begin{equation}
\lambda_i = \sum_{j} \frac 1 2 k_j ( q_{O,j}-q_{R,j})^2
\tag{1}
\end{equation}

Where k is a force constant and q is the displacement of the core components of the oxidized and reduced species. This equation is used to evaluate the energy difference between the vibration modes before and after the electron transfer reaction.

\begin{equation}
\lambda_O = \frac{e^2}{4 \pi \epsilon_0} \left(\frac{1}{2a_1} + \frac{1}{2a_2} - \frac{1}{d}\right) \left(\frac{1}{\epsilon_{op}} - \frac{1}{\epsilon_s}\right)
\tag{2}
\end{equation}

Where a<sub>1</sub> and a<sub>2</sub> are the radii of the reactants including any solvated molecules, and d is the distance between the centers of the two reactants as they exist in their precursor states.[<sup>1</sup>](#bard) From these equations the following generalizations can be made. The standard rate constant, k<sup>0</sup>, will be larger for reactions where O and R very similar. The greater the change of distance or angle between ligands, the solvent shell, or other involved species in the oxidized and reduced states, the greater the reorganization energy will be, and therefore the smaller k<sup>0</sup> will be. 

An example of this can be observed with complexed iron redox couples. Three different iron redox couples are shown in Figure 1 below, where Fe is in the 2+ oxidation state. The largest redox couple with the bulkiest ligands is the Fe(phen)<sub>3</sub><sup>2+/3+</sup>. This particular redox couple, when compared to the others, has shown to have the fastest kinetics.[<sup>2</sup>](#Chen) According to Marcus theory, this is because the ligands are positioned nearly the same distance away from the Fe center before and after electron transfer. Fe(aq)<sup>2+/3+</sup> on the other hand, is relatively small, and experiences large changes in the Fe-ligand bond distances before and after the electron transfer reaction. Further, Fe(aq)<sup>2+/3+</sup> shows the slowest kinetics of the three iron redox couples.[<sup>2</sup>](#Chen) The metal-ligand bond distances have been experimentally determined by extended X-ray fine structure analysis (EXAFS), where the predictions from Marcus theory on the kinetics of electron transfer hold true.[<sup>3</sup>](#Brunschwig)

<center>
    <img src="./img/ChemStructures.png" width=600px>
    <br>
    <i>
        <b>Figure 1.</b> Chemical Structures of three Fe redox couples with different ligands.
    </i>
</center>
<br>

**Experimental Methods**

Different experimental methods are often used to determine the kinetic rates of redox couples, and gain insight into the reversibility of the reaction. One method that provides an approximate picture of the reversibility of a reaction is the analysis of cyclic voltammograms performed at various ramp rates. For a theoretically wholly reversible reaction, the difference between the potentials at the cathodic and anodic peak currents of a CV scan should be 57 mV.[<sup>4</sup>](#Elgrishi) Further, this observation should be independent of scan rate, however no redox couple is completely reversible in practice and some increase in the difference in potentials is expected with increasing scan rate. If parameters such as concentrations, diffusion coefficients, and electrode area are known for the redox couple, the CV curves can be fit to determine the standard rate constant.

A common experimental method for determining diffusion coefficients of species are Cottrell experiments. This method utilizes chronoamperometry, where potential is held at a constant value and current is measured over time. The benefit of this method is that the current is directly proportional to the number of species being oxidized or reduced at the electrode surface, allowing for a clear picture of the concentration gradient as it evolves over time. At time increases, the diffuse layer slowly grows larger until it reaches a limit.  The current has a inverse square root relationship with time, as shown in equation 3 below. 

\begin{equation}
i(t) = \frac{n F A D_R^{1/2}C_R^*}{\pi^{1/2}t^{1/2}}
\tag{3}
\end{equation}

With knowledge of other parameters such as concentration, the diffusion coefficient can be extracted from the slope of the Cottrell plot, or inverse root time vs current. Using the correct region of the Cottrell plot for determining the diffusion coefficient is important for accurate results. At early times just after the potential is stepped to some value above the equilibrium potential, a significant portion of the current will be contributing towards charging the double layer. Only after about 5R<sub>u</sub>C<sub>d</sub>, where R<sub>u</sub> is the uncompensated resistance and C<sub>d</sub> is the double layer capacitance, will the current be purely faradaic. At long times, typically longer than 20 s, the temperature fluctuations in the solution cause convection and disruption of the uniformity of the diffuse layer, which leads to greater-than-expected currents.[<sup>1</sup>](#bard)


## 2 Experimental 
Three solutions were characterized using cyclic voltammetry and potential step chronoamperometry experiments. A glassy carbon (GC) working electrode was polished using progressively larger grit polishing paper. The first solution contained 5 mM of K<sub>4</sub>Fe(CN)<sub>6</sub>, and 20 mL of 200 mM KCl as the supporting electrolyte. A three-neck round-bottom flask was used to hold the solution and the electrodes. The solution was purged with N<sub>2</sub> gas for 10 minutes before any experiments were conducted. When positioning the working electrode in the cell, care was taken to ensure that the working electrode was at least 2 cm away from a cell wall. An Ag/AgCl reference electrode and a graphite rod counter electrode were used for all the experiments. 

Chronoamperometry experiments were conducted at 100 mV increments from the open circuit potential, towards more anodic potentials. Each potential step collected data for 10 s, followed by a 15 second reductive potential followed by a short open circuit step to allow the diffuse layer to equilibrate. The current range was manually specified for these experiments, and the number of data points collected was increased to near the maximum that the potentiostat allowed for. Cyclic voltammograms were collected using scan rates between 10 mV/s and 1600 mV/s, in a potential window of -0.4 to 0.8 V vs Ag/AgCl.

The second solution contained 5 mM of FeSO<sub>4</sub>, and 20 mL of 200 mM K<sub>2</sub>SO<sub>4</sub>, and was purged prior to experimentation similar to the first solution. Potential step experiments were conducted in an identical manner. The CV experiments were collected at scan rates between 10 mV/s and 400 mV/s, across a potential range of -0.5 to 1.2 V vs Ag/AgCl.

The third solution contained 20 mM of 1,10-phenanthroline and 4.5 mM FeSO<sub>4</sub>, in 20 mL of 200 mM K<sub>2</sub>SO<sub>4</sub>, and was prepared by adding to the second solution. The solution went from having no color to turning a dark red color upon adding 1,10-phenanthroline, as shown in Figure 2. This solution was purged for 10 minutes with inert gas similar to the first two solutions. Potential step experiments were collected in a similar manner as the first two experiments, although at 50 mV increments starting at 100 mV. CV experiments were conducted at scan rates between 10 and 400 mV/s, in a potential range of -0.3 to 1.2 V vs Ag/AgCl. 

<center>
    <img src="./img/Photo.png" width=500px>
    <br>
    <i>
        <b>Figure 2.</b> Image of electrochemical cell after the addition of 1,10-phenanthroline, showing the color change from translucent to dark red.
    </i>
</center>
<br>

Lastly, the collected CV data was used to fit simulated CV curves using the EC-Lab CV simulator analysis tool. The nominal values for the active species concentration, transfer coefficient, scan rate, potential range, and electrode area were entered into the simulation parameters, while the measured values for the diffusion coefficient and the standard potential were used. The value of standard rate constant was altered in the simulation parameters until the simulated results fit the measured data. If needed, the other parameters were altered until the simulated results fit the measured data.



## 3 Results
### 3.1 Potential Step Experiments
Potential step experiments were conducted on the Fe(CN)<sub>6</sub><sup>4-</sup> containing solution, at 100, 200, 300, and 400 mV overpotential. E<sub>eq</sub> was measured at -135 mV vs Ag/AgCl. Figure 3 below shows the resulting Cottrell slopes extracted from the various potential steps and the Cottrell slope that was extracted from the 400 mV potential step. The slopes appear linear between 8 and 17 s<sup>-1/2</sup>, where at lower t<sup>-1/2</sup>, the slope begins to flatten out, and the slopes of the different potential steps appear more similar. Using the Cottrell equation, given in equation 1, the diffusion coefficient was extracted from the slope, and found to be 3.17 x 10<sup>-6</sup> cm<sup>2</sup>/s.

<table><tr>
    <td> <img src="./Figure1.png" width=600px> </td>
    <td> <img src="./img/Figure004.png" width=600px> </td>
    </tr>
</table>
<center><i>
    <b>Figure 3.</b> <b>Left:</b> Cottrell plot for the Fe(CN)<sub>6</sub><sup>4-</sup> CA experiments at four different potential steps. <b>Right:</b> Cottrell plot of the 400 mV potential step and the linear fit used to determine the diffusion coefficient.
    </i>
</center>
<br>


The results of the FeSO<sub>4</sub> potential step experiments and the Cottrell slope was extracted from the 400 mV potential step are shown in Figure 4 below. Here, the slopes appear steep at small t<sup>-1/2</sup>, and flatten out at larger t<sup>-1/2</sup>. The slopes at larger t<sup>-1/2</sup> also appear more similar across the different potentials steps. The diffusion coefficient from this potential step was found to be 3.68 x 10<sup>-6</sup> cm<sup>2</sup>/s.


<table><tr>
    <td> <img src="./Figure2.png" width=600px> </td>
    <td> <img src="./img/Figure008.png" width=600px> </td>
    </tr>
</table>

<center><i>
        <b>Figure 4.</b> <b>Left:</b> Cottrell plot for the FeSO<sub>4</sub> CA experiments at four different potential steps. <b>Right:</b> Cottrell plot of the 400 mV potential step and the linear fit used to determine the diffusion coefficient.
    </i>
</center>
<br>



The results of the 1,10-phenanthroline Fe solution (Fe(phen)<sub>3</sub>) potential step experiments are shown in Figure 5 below. All of the potential steps from this experiment yielded relatively linear curves across the entire t<sup>-1/2</sup> range. The 450 mV potential step was used for Cottrell analysis and the diffusion coefficient was found to be 3.31 x 10<sup>-6</sup> cm<sup>2</sup>/s.

<table><tr>
    <td> <img src="./Figure3.png" width=600px> </td>
    <td> <img src="./img/Figure016.png" width=600px> </td>
    </tr>
</table>

<center><i>
        <b>Figure 5.</b> <b>Left:</b> Cottrell plot for the Fe(phen)<sub>3</sub> experiments at eight different potential steps. <b>Right:</b> Cottrell plot of the 450 mV potential step and the linear fit used to determine the diffusion coefficient.
    </i>
</center>
<br>

### 3.2 Cyclic Voltammetry Experiments
CV experiments were performed on the three different solutions across a range of scan rates. The CV curves collected for Fe(CN)<sub>6</sub><sup>4-</sup> are shown in Figure 6 below. The difference between the potentials of peak anodic and cathodic current were calculated as a function of scan rate. At the lowest scan rate of 10 mV/s, the peak difference was 72.9 mV, while at 400 mV/s it was found to be 115.4 mV. E<sup>1/2</sup> was measured to be 0.246 V vs Ag/AgCl.

<center>
    <img src="./Figure4.png" width=600px>
    <br>
    <i>
        <b>Figure 6.</b> Cyclic voltammograms of Fe(CN)<sub>6</sub><sup>4-</sup> at scan rates between 10 mV/s and 1600 mV/s. The red dots on the CV curve correspond to the measured anodic wave peaks and the blue dots correspond to the measured cathodic wave peaks.
    </i>
</center>
<br>

The CV experiments performed on the FeSO<sub>4</sub> solution are shown in Figure 7 below. The peaks of the cathodic and anodic waves are clearly separated by a significant degree. The separation in peak potentials at 10 mV/s was found to be 388.6 mV, and at 400 mV/s the separation was found to be 700.5 mV. E<sup>1/2</sup> was measured to be 0.441 V vs Ag/AgCl.

<center>
    <img src="./Figure5.png" width=600px>
    <br>
    <i>
        <b>Figure 7.</b> Cyclic voltammograms of FeSO<sub>4</sub> at scan rates between 10 mV/s and 400 mV/s. The red dots on the CV curve correspond to the measured anodic wave peaks and the blue dots correspond to the measured cathodic wave peaks.
    </i>
</center>
<br>

The CV experiments performed on the Fe(phen)<sub>3</sub> solution are shown in Figure 8 below. The peaks current potentials of the anodic and cathodic sweeps appear close to one another at all scan rates. At 10 mV/s, the separation in peaks was 59.5 mV, while at 400 mV/s it was 72.7 mV. E<sup>1/2</sup> was measured to be 0.895 V vs Ag/AgCl.

<center>
    <img src="./Figure6.png" width=600px>
    <br>
    <i>
        <b>Figure 8.</b> Cyclic voltammograms of Fe(phen)<sub>3</sub> at scan rates between 10 mV/s and 400 mV/s. The red dots on the CV curve correspond to the measured anodic wave peaks and the blue dots correspond to the measured cathodic wave peaks.
    </i>
</center>
<br>
