**Intro**
This project details the building of a potentiometric chloride sensor. It is built using an Ag/AgCl indicator electrode, a KCl-agar salt-bridge reference junction, and a TL072 op-amp voltage follower.

**How it works**
1) The Ag/AgCl indicator electrode has a potential across it that varies with Cl⁻ concentration.
2) The reference electrode, connected via the agar/KCl salt bridge, maintains a stable, constant potential.
3) The TL072 op-amp, configured as a voltage follower, allows the multimeter to read the potential difference without drawing current that would change the potential difference.
4) The Total Ionic Strength Adjustment Buffer (TISAB) is added to all solutions to prevent contaminating ions from messing up results.

**Bill of Materials**
| Material | Function |
|---|---|
| 99.9% Silver Wire | Electrodes |
| 9V Battery | Powers the op-amp |
| TL072 (Op-Amp) | Eliminates voltmeter current draw effects |
| 1 kΩ Resistor | Filters noise|
| 100 nF Capacitors | RC filtering |
| Male, hybrid, and alligator wires; battery clip | Circuit connections |
| Aquarium tubing | Houses the agar salt bridge |
| Agar powder | Forms the salt bridge |
| Potassium chloride (KCl) | Salt bridge ion source |
| Sodium nitrate (NaNO₃) | TISAB component |
| Sodium chloride (NaCl) | Test solution preparation |
| Hydrochloric acid (HCl) | Forms AgCl layer on electrodes |
| Acetic acid (CH₃COOH) | TISAB component |

**Build Procedure**
1) Chlorinate the silver wires by connecting a battery to the electrodes and putting them in 1.0 M HCl for 10 minutes. A purple-grey coating should form in the area dipped in HCl.
2) Create 100 mL of 3 M KCl solution and add 1-2 grams of Agar powder while heating and stirring thoroughly.
3) Take the solution and put it into aquarium tubing, and wait for it to solidify. This should take 2-3 minutes.
4) Assemble the circuit detailed in the KiCad schematic.
5) Test and calibrate with different chloride concentrations.

<img width="1080" height="516" alt="image" src="https://github.com/user-attachments/assets/06305028-f9eb-4d49-806d-5b42db26b5b3" />

