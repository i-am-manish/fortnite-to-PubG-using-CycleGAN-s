# fortnite-to-PubG-using-CycleGAN-s

CycleGANs are used for cross-domain image style transfer. They can be trained to convert images of one domain to another domain.

1.Train two deep networks, one generator and one discriminator.

2.Discriminator will learn over time to distinguish between real and fake images of Fortnite.

3.Generator will be trained to convert the input image from original domain to target domain.It is made up of three major blocks.The first encoding of Fortnite screenshot to low dimension. Then to transform into an encoding that represents PUBG in that same latent space. Then the decoder toget output PubG image.

4.Train another set of generator/discriminator that reconstructs image in original domain from the fake domain.

5.Cycle loss is calculated from how different is original from fake.

Moreover in results,it even learnt to replace the health meter at the bottom of the screen with the gun and ammo indicator of PUBG! 
You can check results here https://youtu.be/xkLtgwWxrec




