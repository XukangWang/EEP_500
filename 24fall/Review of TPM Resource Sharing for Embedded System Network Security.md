### Review of "TPM Resource Sharing for Embedded System Network Security"

**1. Main Technical Contributions**

This article proposes a new architecture that combines Discrete Trusted Platform Module (dTPM) and Software TPM (SWTPM) in a resource sharing framework to protect embedded system networks. The core idea is to reduce the cost and complexity of large-scale deployment by equipping dTPM only at the central node in the network, while other nodes use SWTPM. This architecture utilizes IBM Authentication Client Server (IBMACS) to facilitate secure authentication and ensure system integrity is maintained on all nodes. The main contributions include the innovative use of dTPM to store and manage critical encrypted data, as well as the use of SWTPM to provide TPM like functionality on resource constrained nodes. The proposed method ensures the integrity of SWTPM components is verified through regular challenges initiated by the central node. In addition, this article also addresses the cost issue associated with deploying dTPM on all nodes, providing a scalable and secure alternative solution for embedded IoT networks.

**2. Possible Applications**

The proposed architecture is particularly relevant to IoT and edge computing applications, where cost-effective security measures are crucial. Potential use cases include smart city infrastructure such as energy-efficient streetlight systems, industrial automation networks, and medical IoT devices. By adopting SWTPM in most nodes, this framework enables large-scale deployment of security sensitive systems without incurring the high cost of equipping each device with dTPM. It also applies to scenarios such as autonomous vehicle communication networks and distributed environmental monitoring systems, where ensuring data integrity is critical. The ability to detect tampering and unauthorized modifications in real-time enhances its applicability to critical task applications.

**3. Possible Future Extensions**

Future extensions can explore enhancing the security of SWTPM to mitigate vulnerabilities caused by its software based nature. Integrating advanced encryption technologies, such as homomorphic encryption, can further strengthen the system. Another promising direction is to use machine learning models trained on proof logs to automate anomaly detection. Expanding compatibility with a wider range of hardware platforms, including low-power devices, can enhance its applicability. In addition, integrating this architecture with Collaborative Intrusion Detection Systems (CIDS) will provide comprehensive security coverage across distributed networks.

**4. Choice of Paper and Personal Interest**

I chose this paper because it focuses on network security in embedded systems, which is a topic directly related to my academic and professional interests. The innovative use of TPM resource sharing is consistent with my desire to develop cost-effective, scalable, and secure solutions for IoT networks. As a master's student specializing in embedded software engineering, I find the actual implementation and experimental results particularly inspiring. This article has deepened my understanding of TPM functionality and its role in building trust across distributed systems. It also provides valuable insights into the challenges of expanding security measures in resource constrained environments, which is crucial for my ongoing research and future projects.

**5. Review Details**

- **Reviewer:** Xukang Wang
- **Date:** November 12, 2024
- **Citation:** D. -C. Chen, G. -R. Chen, Y. -K. Lin, and Y. -P. Liao, "TPM Resource Sharing for Embedded System Network Security," 2024 10th International Conference on Applied System Innovation (ICASI), Kyoto, Japan, 2024, pp. 18–20, doi: 10.1109/ICASI60819.2024.10547999.