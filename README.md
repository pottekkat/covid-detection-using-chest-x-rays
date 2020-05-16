# Detecting COVID-19 infection using Chest X-rays

The exponential increase in COVID-19 patients is overwhelming the healthcare systems across the world and it continues to have a devastating effect on the population. A critical step in the fight against the virus is a fast and reliable testing technique. The conventional techniques (RT-PCR) is costly and more importantly they take time and have limited sensitivity.

While the diagnosis is confirmed using polymerase chain reaction (PCR), infected patients with pneumonia may present on chest X-ray and computed tomography (CT) images with a pattern that is only moderately characteristic for the human eye. In late January, a Chinese team published a paper detailing the clinical and paraclinical features of COVID-19. They reported that patients present abnormalities in chest CT images with most having bilateral involvement.

Detecting possible COVID-19 infection from Chest X-ray will provide a faster and reliable method that could be used with the conventional tests for faster detection. Since most modern healthcare systems are equipped with digitized X-ray machines, there are no additional costs or resources required for testing.

The system used consists of a model which has been trained on 250+ Chest X-ray images. The model uses computer vision techniques to determine the anomalies in the images and determines whether the patient has been infected with COVID-19. Most of this anomalies are invisible to the naked eye as shown below.

The model when tested showed an accuracy of 99%. i.e the model can effectively predict if a person is affected by COVID-19 with Chest X-rays with almost 100% certainty.
