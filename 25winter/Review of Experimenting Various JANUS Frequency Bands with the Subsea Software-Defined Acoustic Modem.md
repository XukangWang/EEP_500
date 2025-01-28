### Review of "Experimenting Various JANUS Frequency Bands with the Subsea Software-Defined Acoustic Modem"

### 1. Main Technical Contributions

The paper introduces the Subsea Software-Defined Acoustic Modem (SuM), a low-cost, Raspberry Pi-based platform designed for underwater acoustic communication and experimentation. Key contributions include:

- **Hardware Innovations:** The SuM platform integrates a Raspberry Pi, HiFiBerry DAC+ADC Pro, and a custom-designed SuM HAT, forming a compact three-layer stack. The system is flexible enough to support multiple underwater acoustic transducers, offering adaptability for different frequencies and power requirements.
- **Performance Evaluation:** Extensive testing of the SuM modem with the JANUS waveform in salt and freshwater environments demonstrates its robustness and reliability. The experiments achieved communication ranges of several hundred meters with high-frequency transducers and up to kilometers with low-frequency transducers.
- **Cost Accessibility:** By leveraging off-the-shelf components, the SuM modem drastically reduces the cost barrier for underwater communication research, making it accessible to smaller research groups and startups.
- **Standards Compliance:** The modem supports JANUS, the NATO-standardized underwater communication protocol, enabling interoperability with existing systems.

### 2. Possible Applications

The SuM modem’s affordability and versatility open doors to a range of applications, including:

- **Underwater Environmental Monitoring:** Deployable for real-time data collection in remote marine and freshwater ecosystems.
- **Aquaculture:** Facilitates low-cost monitoring and control in fish farming operations.
- **Diver Communication:** Enables cost-effective communication solutions for recreational and professional divers.
- **Underwater Robotic Networks:** Serves as a communication backbone for autonomous underwater vehicles (AUVs) and robotic swarms.
- **Education and Research:** Provides a platform for students and researchers to explore underwater communication without incurring high costs.

### 3. Possible Future Extensions

Future work could focus on the following areas:

- **Enhanced Modulation and Coding Schemes:** Explore advanced algorithms to improve data transmission rates and reliability under adverse underwater conditions.
- **Full-Duplex Communication:** Reintroduce full-duplex capabilities through optimized hardware design to increase efficiency.
- **Improved Scalability:** Adapt the platform for large-scale deployment in multi-hop underwater networks.
- **Integration with IoT Ecosystems:** Develop interfaces for seamless integration with surface-level IoT systems for real-time monitoring and control.
- **Advanced Testing:** Extend evaluations to harsher environments, such as deep-sea conditions and areas with high acoustic noise.

### 4. Personal Interest and Knowledge Gained

I chose this paper because of my interest in embedded systems and their applications in communication technologies. The innovative use of a Raspberry Pi-based system for underwater communication resonates with my specialization in embedded software engineering. The paper provided valuable insights into hardware-software integration for underwater acoustic systems and broadened my understanding of how cost-effective solutions can drive research and industrial applications. Moreover, the discussion on adapting the JANUS protocol deepened my appreciation for standards-compliant designs in resource-constrained environments.

### 5. Scholarly Citation

Singh S, Crispo M, Bousquet J-F, Aljendi S. A Janus compatible software-defined underwater acoustic multiple-input multiple-output modem. International Journal of Distributed Sensor Networks. 2021;17(4). doi:10.1177/15501477211010663

**Reviewer:** Xukang Wang
**Date of Review:** January 27, 2025