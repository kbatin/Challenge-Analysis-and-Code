# Challenge Analysis and Code - Analyzing the Impact of Hurricane Maria Using NDVI and Object Detection

In this project, we analyze the environmental impacts of Hurricane Maria using Sentinel-2 satellite data, with a focus on vegetation health and damage assessment through NDVI (Normalized Difference Vegetation Index) analysis and object detection. 

### Key Sections:

#### Introduction to the Challenge**
- Puerto Rico’s unique geography and climate make it particularly vulnerable to hurricanes like Maria. This challenge aims to assess the vegetation health of the island both before and after the hurricane using satellite data. We explore how areas were affected, the extent of recovery, and the implications for disaster management and resilience planning.

#### Actionable Recommendations
- **Recommendation 1:** The government should prioritize providing affordable, disaster-resistant housing by collaborating with non-profits and architects, such as Marvel Architects, to build resilient homes.
- **Recommendation 2:** Improving disaster preparedness is essential. Puerto Rico should adopt a comprehensive disaster education approach, inspired by Japan, to enhance communication and preparedness across the island.
- **Recommendation 3:** Implement parametric insurance models to provide quicker disaster recovery funding based on specific hazard criteria like hurricane strength. This will improve the financial resilience of communities.

#### Analysis and Code
- Our NDVI analysis used Sentinel-2 data to assess the changes in vegetation health across multiple time points before and after Hurricane Maria. We developed several visualizations to highlight the most affected areas. Additionally, we labeled pre- and post-event images and built a YOLO model to detect and classify areas impacted by the hurricane. Despite challenges in model precision (mAP50 of 0.3), further refinements would improve disaster response capabilities.

#### Conclusion
- Hurricane Maria revealed significant vulnerabilities in Puerto Rico’s infrastructure and vegetation. Our analysis highlights the importance of disaster-resistant housing, comprehensive disaster planning, and effective insurance models to enhance recovery efforts. Further analysis could explore more advanced machine learning techniques to provide more accurate predictions and support future disaster management strategies.

#### Future Steps
- Given more time, we would expand the dataset, include more diverse land areas, and implement advanced machine learning techniques like Faster R-CNN to improve model accuracy. We would also aim to detect subtle environmental changes that could impact long-term recovery.

#### Feedback for EY
- One of the most challenging aspects of this project was annotating over 10,000 images, which required clear communication and teamwork across multiple nations. Despite the difficulties, this collaboration enhanced the accuracy of our annotations. The NDVI analysis provided valuable insights into the long-term ecological effects of hurricanes and the importance of green spaces in disaster resilience.



Check the project [here](https://github.com/kbatin/Challenge-Analysis-and-Code/blob/main/Coastal_Resiliensce_T1-7.ipynb)


<sub>This is a group project.</sub>
