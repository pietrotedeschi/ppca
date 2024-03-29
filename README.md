## PPCA: Privacy-Preserving Collision Avoidance for Autonomous Unmanned Aerial Vehicles
`PPCA` is a lightweight, distributed, and privacy-preserving privacy-preserving <b>collision avoidance</b> scheme for autonomous UAVs. It integrates and turns privacy-preserving proximity testing solutions, traditionally adopted in online geo-social networks, into a real-time interactive approach to detect co-location among moving entities, and to avoid approaching collisions.

<p align="center">
     <img alt="Setup Phase" src="./img/scenario.png" width="800">
</p>

The details are provided in the <a href="https://ieeexplore.ieee.org/document/9736583">paper</a>, accepted and published by the prestigious IEEE Transactions on Dependable and Secure Computing.

## Formal verification with ProVerif
The security properties of `PPCA` have been verified formally and experimentally by using the open-source tool <a href="https://prosecco.gforge.inria.fr/personal/bblanche/proverif/">ProVerif 2.01</a>, demonstrating enhanced security protection with respect to state-of-the-art approaches.

In order to test the security properties, download the file <a href="ppca.pv">ppca.pv</a> and run: `./proverif ppca.pv | grep "RESULT"`.
Further, in order to verify that the location is a strong secret (i.e. the attacker cannot launch offline guessing attacks on the location value), please follow the guidelines inside the code.

<p align="center">
  <img src="./img/proverif.png" alt="PPCA" width="700">
</p>

## Demo Video

[![PPCA](https://img.youtube.com/vi/2LW_ZFk6ZS0/0.jpg)](https://www.youtube.com/watch?v=2LW_ZFk6ZS0)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Developers
(^) Pietro Tedeschi        (pietro dot tedeschi at tii dot ae)<br />
(-) Savio Sciancalepore    (s dot sciancalepore at tue dot nl)<br />
(+) Roberto Di Pietro      (rdipietro at hbku dot edu dot qa)<br />

(^) Technology Innovation Institute, Secure Systems Research Center, Abu Dhabi, United Arab Emirates<br />
(-) Security Group - Faculty of Mathematics and Computer Science, Eindhoven University of Technology (TU/e), Eindhoven, The Netherlands<br />
(+) Division of Information and Computing Technology (ICT), College of Science and Engineering (CSE), Hamad Bin Khalifa University (HBKU), Doha, Qatar<br />

## License
`PPCA` is released under the GNU General Public License v3.0 <a href="LICENSE">license</a>.
