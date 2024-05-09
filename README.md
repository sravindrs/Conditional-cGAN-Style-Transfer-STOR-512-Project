# Conditional-cGAN-Style-Transfer-STOR-512-Project
#This project explores the development and optimization of a Generative Adversarial Network, specifically a Conditional CycleGAN, designed to transform human facial images
into comic-style representations. The architecture comprises two generators and two discriminators, each responsible for transforming and validating images across domains while
ensuring cycle consistency. This setup aims to not only map between domains but also
to recover the original images post-transformation, thus maintaining a continuous transformation loop. The model employs adversarial and cycle consistency losses to ensure
the generated images are both indistinguishable from real images and capable of reverting
to their original forms, enhancing image quality and fidelity to the intended style. Optimization techniques such as gradient penalty and adaptive instance normalization were
utilized to stabilize training and adapt to diverse inputs, while data augmentation broadened the model’s exposure to varied facial features. Supported by high-performance GPU
computing, these strategies expedited training and facilitated real-time adjustments. The
efficacy of the Conditional CycleGAN was validated through qualitative assessments and
quantitative metrics like the Inception Score and cycle-consistency loss, confirming the
model’s ability to effectively bridge distinct visual domains and showcasing the potential
of CycleGANs in advanced image transformation tasks
