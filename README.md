# Project 3: Electrochemical Kinetics and Electrocatalysis
### Tanner Leo, University of Oregon, Electrochemistry Lab, November 9<sup>th</sup>

## Introduction
Both thermodynamics and kinetics play important roles in determining rates and potentials required to induce electron transfer reaction. Many of the reactions that have practical use to electrochemical engineers pursuing improved clean energy technologies, entail multi-step electron-transfer processes. For example, electrochemical water splitting involves a four-electron transfer for the anodic oxidation reaction and a two-electron transfer process for the cathodic reduction reaction.<cite id="vwe6l"><a href="#zotero%7C7738305%2F23QJR3YX"><sup>1</sup></a></cite> This makes the kinetics for the electrochemical reaction slow, requiring large overpotentials before the activation barrier for the reaction is overcome. While the thermodynamic description of water splitting suggests potentials of 1.23 V vs NHE will drive the reaction, a potential of 1.8 V vs NHE is often required.<cite id="0tisc"><a href="#zotero%7C7738305%2FFJXNNLJZ"><sup>2</sup></a></cite>

Water splitting consists of two half reactions occurring at the cathode and anode: the production of H<sub>2</sub> at the cathode, also known as hydrogen evolution reaction (HER), and the production of O<sub>2</sub> at the anode, also known as oxygen evolution reaction (OER). Depending on the medium, the equilibrium potential for the reaction, E<sub>eq</sub> is subject to change. In an acid medium with H<sup>+</sup> at unit activity, the half reactions are given by equations 1 & 2 below. 

\begin{equation}
2H^+ + 2e^- \leftrightarrows H_2
,\ E^0 =\text{  0 V vs SHE}
\tag{1}
\end{equation}

\begin{equation}
2H_2O \leftrightarrows O_2 + 4H^+ + 4e^-
,\ E^0 =\text{  1.23 V vs SHE}
\tag{2}
\end{equation}

However, in a basic medium with OH<sup>-</sup> at unit activity, the two half reactions are given by equations 3 and 4 below. 

\begin{equation}
2H_2O + 2e \leftrightarrows H_2 + 2OH^-
,\ E^0 =\text{  -0.83 V vs SHE}
\tag{3}
\end{equation}

\begin{equation}
2H_2O \leftrightarrows 2H_2 + O_2
,\ E^0 =\text{  0.4 V vs SHE}
\tag{4}
\end{equation}

Therefore, depending on the half reaction of interest, the pH of the electrolyte is of great importance to the potentials required to drive either half reaction. 

Kinetics play a vitally important role in electrochemical reactions. 
(talk about the butler volmer equation, tafel plots, etc).

The efficiency of HER and OER are highly dependent upon the active catalyst or electrode driving the reaction. Pt is one of most widely used and most efficient catalysts for driving HER. Platinum black was used more frequently as a catalyst in the 1950s and 1960s for both acid and alkaline fuel cells, due to it's high surface area, although since then platinum metal dispersed on a carbon support (Pt/C) has been the more popular choice due to improvements in efficiency.<cite id="yfmty"><a href="#zotero%7C7738305%2FUAWXUCDV"><sup>3</sup></a></cite> Cu has been studied as an electrocatalyst for HER, with results showing relatively poor catalytic performance compared to the alternatives, however there is ongoing research on how it's catalytic efficiency may be improved.<cite id="0hq5c"><a href="#zotero%7C7738305%2FNKBKB4K6"><sup>4</sup></a></cite>

Two of the most efficient transition state metal OER catalysts are Ni and Co.<cite id="gmboc"><a href="#zotero%7C7738305%2F36S6EZDF"><sup>5</sup></a></cite> There have been many reports in the literature of Fe doping of Ni(OH)<sub>2</sub> having dramatic effects on the efficiency of OER.<cite id="8rp3d"><a href="#zotero%7C7738305%2FJQ85JZ3M"><sup>6</sup></a></cite><sup>,</sup><cite id="b0jj9"><a href="#zotero%7C7738305%2FWB238N6A"><sup>7</sup></a></cite><sup>,</sup><cite id="8u5ac"><a href="#zotero%7C7738305%2F2WSTQX2W"><sup>8</sup></a></cite> Fe-doped can be electrodeposited from a solution of Ni(NO<sub>3</sub>)<sub>2</sub> and FeCl<sub>2</sub>, following the chemical reactions shown in equations 5 and 6 below.

\begin{equation}
NO_3^- + 7H_2O + 8e^- \rightarrow NH_4^+ + 10 {OH}^-
\tag{5}
\end{equation}

\begin{equation}
M^{n+} + nOH^- \rightarrow M(OH)_n
\tag{6}
\end{equation}

Where M is either Fe or Ni, and n is the oxidation state (2+ for these metals). When FeCl<sub>2</sub> is in a far lower concentration than Ni(NO<sub>3</sub>)<sub>2</sub>, it serves as a dopant, periodically replacing lattice sites where Ni would normally reside.<cite id="o828n"><a href="#zotero%7C7738305%2FZA3KF2R3"><sup>9</sup></a></cite>
