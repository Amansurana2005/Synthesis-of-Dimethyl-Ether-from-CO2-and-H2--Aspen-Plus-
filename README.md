# Synthesis-of-Dimethyl-Ether-from-CO2-and-H2- Aspen-Plus-

Elaborate Portfolio Description
Project Title: Dimethyl Ether (DME) Process Synthesis and Optimization

Challenge: The objective of this project was to design and simulate a highly efficient process for the catalytic synthesis of Dimethyl Ether (DME) from carbon dioxide and hydrogen. The core challenge was to integrate a multi-stage reactor system with critical heat transfer and separation steps, ensuring the final product stream met purity and yield requirements while minimizing the loss of valuable components in a continuous recycle loop.

Methodology:

Process Flowsheet Design: The simulation was built in Aspen Plus, modeling a two-reactor system in series. This included a 55-fold isentropic compressor, two isothermal CSTRs (12 m 
3
  each) operating at different temperatures (500∘ C and 220∘ C), and a series of heat exchangers and flash separators to manage temperature and phase changes.

Thermodynamic and Kinetic Modeling: The simulation employed the RK-Soave and NRTL-2 property methods to accurately model the non-ideal behavior of the gas mixture. Two distinct equilibrium reactions were defined: a fugacity-based reaction in the first reactor and a partial-pressure-based reaction in the second, reflecting the specific kinetic conditions.

Design Specification and Optimization: To meet a critical process constraint, two Design Spec blocks were implemented. The first Design Spec was used to control the temperature of the first chiller, minimizing the amount of water carried over to the second reactor. The second Design Spec was used to minimize methanol loss in the purge stream from the second flash tank by adjusting the final chiller temperature.

Recycle Loop Implementation: A 90% recycle loop was integrated to enhance overall process efficiency. This involved splitting the final vapor product, depressurizing the recycled stream to atmospheric conditions, and routing it back to the feed mixer for re-compression.

Results and Impact:

Enhanced Water Removal: The first Design Spec successfully reduced the water vapor flow into the second reactor by 99.3%, from an initial value of 0.822 kmol/hr to a final value of 0.005 kmol/hr, protecting the downstream catalyst and improving reaction efficiency.

Component Loss Minimization: The second Design Spec was successfully converged, limiting the molar flow rate of methanol in the purge stream to 0.07 kmol/hr, well below the target tolerance of 0.1 kmol/hr.

Final Product Output: The converged simulation predicted a total DME production rate of 26.24 kmol/hr, demonstrating the viability and effectiveness of the proposed process design.

Operational Integrity: The entire flowsheet, including the complex recycle loop, was successfully converged and solved, proving proficiency in handling advanced simulation challenges and ensuring the robustness of the design.
