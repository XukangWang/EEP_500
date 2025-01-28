### Review of "Adaptive OFDM Modulation for Underwater Acoustic Communications: Design Considerations and Experimental Results"

#### 1. Main Technical Contributions of the Paper

The paper “Adaptive OFDM Modulation for Underwater Acoustic Communications: Design Considerations and Experimental Results” presents a pioneering approach to improving underwater acoustic (UWA) communication through adaptive orthogonal frequency-division multiplexing (OFDM). Key contributions include:

1. **Doppler Compensation and Sparse Channel Estimation**: The paper addresses the challenges posed by Doppler effects in UWA channels by developing a framework for motion compensation and sparse multipath channel estimation.
2. **Channel Prediction and Adaptive Modulation**: A linear recursive least squares (RLS) algorithm is proposed for predicting channel states one travel time ahead, enabling adaptive modulation and power allocation.
3. **Experimental Validation**: Unlike most prior works, the effectiveness of the proposed adaptive schemes is validated using real-time at-sea experiments, demonstrating significant improvements in system throughput compared to nonadaptive modulation.
4. **Two Adaptive Schemes**: The first scheme adjusts modulation levels with uniform power allocation, while the second adapts both modulation levels and power allocation. The latter achieves higher throughput by optimizing resource allocation across subcarriers.
5. **Feedback Mechanisms**: The paper evaluates feedback strategies, showing that feeding back sparse channel impulse responses significantly reduces overhead compared to transmitting modulation and power levels directly.

#### 2. Possible Applications of the Work

The work has broad applications in underwater communications, particularly in:

1. **Oceanographic Research**: Real-time high-rate data transfer for remote monitoring and control of underwater equipment.
2. **Defense and Naval Operations**: Secure, efficient communication for submarines and autonomous underwater vehicles (AUVs).
3. **Environmental Monitoring**: Long-term deployment of sensor networks for marine ecosystem studies and climate change tracking.
4. **Offshore Industry**: Reliable communication for oil and gas exploration, pipeline monitoring, and robotic interventions.

#### 3. Possible Future Extensions of the Work

The paper opens several avenues for future research:

1. **Robustness under High Mobility**: Extending the methods to support rapidly varying channels due to fast-moving platforms like AUVs.
2. **Integration with Machine Learning**: Leveraging data-driven approaches for adaptive modulation and channel prediction to handle complex nonstationary environments.
3. **Scalability for Large Networks**: Adapting the schemes for multi-node networks with interference management.
4. **Energy Efficiency**: Optimizing power allocation for energy-constrained systems such as underwater sensor networks.

#### 4. Reason for Choosing the Paper

My interest in this paper stems from its relevance to embedded systems and real-time adaptive communication—areas closely aligned with my academic focus. As a Master’s student specializing in embedded software at UW ECE, I have studied signal processing and communication theory, but this paper expanded my understanding of their application to UWA environments. The experimental rigor and practical insights provided by the real-world trials made this study particularly enlightening.

#### 5. Scholarly Citation

A. Radosevic, R. Ahmed, T. M. Duman, J. G. Proakis and M. Stojanovic, "Adaptive OFDM Modulation for Underwater Acoustic Communications: Design Considerations and Experimental Results," in IEEE Journal of Oceanic Engineering, vol. 39, no. 2, pp. 357-370, April 2014, doi: 10.1109/JOE.2013.2253212.

**Keywords**: Adaptive modulation; feedback; orthogonal frequency-division multiplexing (OFDM); underwater acoustic (UWA) communication.

**Reviewer:** Xukang Wang
**Date of Review:** January 23, 2025