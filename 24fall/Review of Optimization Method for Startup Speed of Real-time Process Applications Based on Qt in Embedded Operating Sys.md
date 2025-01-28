### Review of "Optimization Method for Startup Speed of Real-time Process Applications Based on Qt in Embedded Operating System"

**1. Main Technical Contributions**

This article proposes a new optimization method to improve the startup speed of Qt based real-time process (RTP) applications in embedded operating systems. The main contributions include introducing a font pre rendering strategy and using an independent ROMFS file system for resource preloading. These methods address common bottleneck issues in embedded systems, such as slow loading of Qt dynamic libraries and time-consuming Chinese font parsing. Font pre rendering converts Chinese fonts into images preloaded into memory, eliminating the need for runtime font calculations. The independent ROMFS file system organizes basic resources (including pre rendered fonts and dynamic libraries) into a read-only memory file system, significantly reducing disk I/O during application startup. The experimental results showed a significant improvement in startup speed. When the first RTP application only used font pre rendering, the startup speed increased by 65%. When combined with ROMFS pre loading, the startup time decreased by 27%.

**2. Possible Applications**

This optimization method is particularly useful for embedded systems that require high responsiveness, such as automotive infotainment systems, industrial HMI (Human Machine Interface) panels, and consumer electronics products such as smart appliances. It is also applicable to public information systems, including information kiosks and ATM interfaces, where fast startup times directly affect user experience. In addition, this approach can benefit wearable devices, IoT gateways, and other systems where resource constraints make efficient startup processes crucial. It focuses on pre rendering Chinese fonts, making it particularly suitable for applications in regions with a large number of Chinese users.

**3. Possible Future Extensions**

Future work can explore optimizing the startup process of other complex font systems, such as Arabic or Tiancheng fonts, and expanding the applicability of font pre rendering strategies. In addition, integrating this method with advanced embedded platforms with multi-core processors or GPUs can further improve performance by parallelizing resource loading. Expanding the ROMFS file system to support writable segments through a hybrid caching strategy can improve runtime adaptability. This method can also be extended to support dynamic resource compression and decompression to save memory while maintaining fast access speed.

**4. Choice of Paper and Personal Interest**

I chose this paper because I am interested in improving the performance of embedded systems, which is the focus of my academic research and career aspirations. This topic is consistent with my research in embedded software engineering, especially in optimizing human-computer interaction systems. The practical application of Qt in embedded environments is very important because I have participated in projects involving GUI optimization. This article has deepened my understanding of pre caching mechanisms and resource management, providing insights into balancing system constraints and enhancing user experience. Its clear methodology and experimental validation provide a strong framework for my own work.

**5. Review Details**

- **Reviewer:** Xukang Wang
- **Date:** November 12, 2024
- **Citation:** Y. Wang, "Optimization Method for Startup Speed of Real-time Process Applications Based on Qt in Embedded Operating System," 2024 4th International Symposium on Computer Technology and Information Science (ISCTIS), Xi’an, China, 2024, pp. 291–295, doi: 10.1109/ISCTIS63324.2024.10699253.