A. Project Overview

Brief Description of the Project:

This project involves developing an image classification model that can recognize and differentiate 20 related plant species using Google Teachable Machine. A dataset containing
at least 250 images per species was collected and organized into labeled classes. The model was trained, evaluated, and tested to measure its accuracy and performance in identifying plant 
species based on visual features.

Purpose of the Image Classification Model:

The purpose of this image classification model is to automatically identify plant species from images using machine learning techniques. It aims to demonstrate how computer vision
can be applied to classify plants accurately and how dataset quality, training parameters, and evaluation methods affect model performance.

B. Plant Species Section



<table>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/42054f4afd11594c672229a32dafbc9aedb8ac46/PlantsSpecies/Agave.jpg?raw=true" width="180"/></td>
    <td>
      <b>Agave</b><br>
      Scientific Name: Agave<br>
      Description: A drought-resistant succulent known for its thick, spiky leaves that store water and survive in arid desert conditions.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/42054f4afd11594c672229a32dafbc9aedb8ac46/PlantsSpecies/Aloavera.jpg?raw=true" width="180"/></td>
    <td>
      <b>Aloe Vera</b><br>
      Scientific Name: Aloe vera<br>
      Description: A medicinal succulent plant widely used for skin treatment, known for its soothing gel inside thick green leaves.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Cheesebush.jpg?raw=true" width="180"/></td>
    <td>
      <b>Cheesebush</b><br>
      Scientific Name: Ambrosia dumosa<br>
      Description: A desert shrub adapted to dry environments, often found in sandy soils and known for its strong aromatic scent.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/DESERMILKWEED.jpg?raw=true" width="180"/></td>
    <td>
      <b>Desert Milkweed</b><br>
      Scientific Name: Asclepias subulata<br>
      Description: A desert plant that produces milky sap and serves as an important food source for butterflies, especially monarchs.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Date%20Palm.jpg?raw=true" width="180"/></td>
    <td>
      <b>Date Palm</b><br>
      Scientific Name: Phoenix dactylifera<br>
      Description: A tall palm tree cultivated for its sweet edible dates, commonly grown in hot and dry climates.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Desert%20Lavender.jpg?raw=true" width="180"/></td>
    <td>
      <b>Desert Lavender</b><br>
      Scientific Name: Hyptis emoryi<br>
      Description: A fragrant desert shrub with purple flowers that attracts pollinators like bees and butterflies.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Desert%20Rose.jpg?raw=true" width="180"/></td>
    <td>
      <b>Desert Rose</b><br>
      Scientific Name: Adenium obesum<br>
      Description: A beautiful flowering succulent with a thick trunk, known for its pink to red trumpet-shaped flowers.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Elephant%20Bush.jpg?raw=true" width="180"/></td>
    <td>
      <b>Elephant Bush</b><br>
      Scientific Name: Portulacaria afra<br>
      Description: A small-leaved succulent often used as ornamental plant and known for its ability to store large amounts of water.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Elephant%20Tree.jpg?raw=true" width="180"/></td>
    <td>
      <b>Elephant Tree</b><br>
      Scientific Name: Bursera microphylla<br>
      Description: A slow-growing desert tree with thick trunk used for water storage during long dry seasons.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Ephedra%20or%20Mormon%20Tea.jpg?raw=true" width="180"/></td>
    <td>
      <b>Ephedra (Mormon Tea)</b><br>
      Scientific Name: Ephedra spp.<br>
      Description: A desert shrub traditionally used for herbal tea, adapted to survive in harsh dry environments.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Ice%20Plant.jpg?raw=true" width="180"/></td>
    <td>
      <b>Ice Plant</b><br>
      Scientific Name: Mesembryanthemum crystallinum<br>
      Description: A succulent plant with shiny, water-filled cells that look like ice crystals on its surface.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Joshua%20Tree.jpg?raw=true" width="180"/></td>
    <td>
      <b>Joshua Tree</b><br>
      Scientific Name: Yucca brevifolia<br>
      Description: A unique desert tree found in the Mojave Desert, known for its tall branching structure.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Living%20Stone.jpg?raw=true" width="180"/></td>
    <td>
      <b>Living Stone</b><br>
      Scientific Name: Lithops spp.<br>
      Description: A small succulent that mimics stones to avoid predators and survive in dry environments.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Misquite.jpg?raw=true" width="180"/></td>
    <td>
      <b>Mesquite</b><br>
      Scientific Name: Prosopis spp.<br>
      Description: A hardy desert tree that provides shade and food resources in arid regions.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Ocotillo.jpg?raw=true" width="180"/></td>
    <td>
      <b>Ocotillo</b><br>
      Scientific Name: Fouquieria splendens<br>
      Description: A desert plant with long spiny stems that produces bright red flowers after rainfall.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Palo%20Verde.jpg?raw=true" width="180"/></td>
    <td>
      <b>Palo Verde</b><br>
      Scientific Name: Parkinsonia spp.<br>
      Description: A desert tree with green bark that performs photosynthesis even when leaves are absent.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/RubbitBrush.jpg?raw=true" width="180"/></td>
    <td>
      <b>Rabbit Brush</b><br>
      Scientific Name: Ericameria nauseosa<br>
      Description: A yellow-flowering shrub that thrives in dry soils and helps stabilize desert landscapes.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Snake%20Plant.jpg?raw=true" width="180"/></td>
    <td>
      <b>Snake Plant</b><br>
      Scientific Name: Dracaena trifasciata<br>
      Description: A popular indoor plant known for its air-purifying ability and upright sword-like leaves.
    </td>
  </tr>

  <tr>
    <td><img src="https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/blob/4a0ff8954e04f1000c4c5580edddd2d009e8d18f/PlantsSpecies/Soap%20Tree%20Yucca.jpg?raw=true" width="180"/></td>
    <td>
      <b>Soap Tree Yucca</b><br>
      Scientific Name: Yucca elata<br>
      Description: A desert plant used traditionally for soap-making due to its natural saponins.
    </td>
  </tr>

</table>

Link of 20 plants species (https://drive.google.com/drive/folders/1Yp2hWtGn2xr1V-0AZuKZCoUH9gDqbb3r?usp=drive_link)

C. Model Training Details

![Alt Text](https://github.com/juana2003/Plant-Species-Image-Classification/blob/dc8648829c45f95ad54643c8f2a3a2453a4b0d08/Training%20Model%20.jpg)

I chose 50 epochs to ensure that the model has enough opportunities to review and learn the patterns in the dataset without overfitting. 
This number provides a balance between sufficient learning and efficient training time.

The batch size of 16 was selected to balance training speed and accuracy. A moderate batch size allows the model to process a reasonable number of images at a time,
ensuring stable updates to the model weights while keeping the training process efficient.

The learning rate of 0.001 was chosen because it provides a stable and gradual adjustment to the model’s parameters. This prevents large, 
unstable updates that could reduce accuracy while allowing the model to converge effectively during training.

D. Model Evaluation

![Alt Text](https://github.com/juana2003/Plant-Species-Image-Classification/blob/e90648a81bf41ba1ef4eeed4f43ded741fb7a890/Under%20The%20hood.jpg)


E. Model Testing

TEST 1

![TEST 1](https://github.com/juana2003/Plant-Species-Image-Classification/blob/3747df3714dc433c80616957b918ca3be18091ab/Preview%20Test%201.jpg)

TEST 2

![TEST 2](https://github.com/juana2003/Plant-Species-Image-Classification/blob/0c60bfd3d8a2af958fd00ad201c199ba980c0e6f/Preview%20Test%202.jpg)

TEST 3

![TEST 3](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%203.jpg)

TEST 4

![TEST 4](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%204.jpg)

TEST 5

![TEST 5](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%205.jpg)

TEST 6

![TEST 6](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%206.jpg)

TEST 7

![TEST 7](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20test%207.jpg)

TEST 8

![TEST 8](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%208.jpg)

TEST 9

![TEST 9](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%209.jpg)

TEST 10

![TEST 10](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%2010.jpg)



Reflection Questions:

1. How did the number of images per class affect your model’s accuracy? More images per class improved the model’s accuracy because it had more examples to learn from. Classes with fewer images were harder for the model to predict correctly.
2. Which plant species were most commonly misclassified and why? The desert milkweed plant was most commonly misclassified because it has a similar shape to other plants, causing its percentage to be distributed among other species that look alike.
3. How did changing the epochs, batch size, or learning rate affect the training results? Using 50 epochs, a batch size of 16, and a learning rate of 0.001 provided stable learning and balanced accuracy.
4. What challenges did you encounter during dataset collection and labeling? Even though I uploaded 250 images per class, not all of them were included in the training. About 1–10 images per class were missing and were not captured by the system.
5. If you were to improve your model, what specific changes would you make and why? I would add more images and apply data augmentation to make the model more robust. I would also fine-tune the epochs or learning rate to improve overall accuracy.

