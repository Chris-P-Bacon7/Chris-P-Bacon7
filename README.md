# Hi, I'm Chris 💻👀🖥️👀

Welcome to my GitHub profile! I'm a second-year ECE (Electrical and Computer Engineering) student at the University of Toronto, and I am more focused on the computer engineering side of things. Some fun facts about me:
- I love music, and I play the piano and the violin. If you ever decide to tune in, you can catch me playing some Pop/Rock tunes or classical pieces from famous composers like Liszt, Chopin, or Beethoven (I'm a Romantic-era kinda pianist 🎹)
- On the more active side, my favourite sport is swimming, and I also like playing volleyball and badminton. My goal for Summer 2027 is to complete a full triathlon! I'm also on my school's dragon boat team (Iron Dragons)
- A hot dog is **not** a sandwich (I'm open to debate, but I will never agree to otherwise :P 🌭≠🥪)


Ok. Enough about me. Onto more technical and professional kind of things. 🫡

## Why classical computer vision

I loveeeee computer vision, especially classical computer vision in an era where the field is dominated by machine learning and artificial intelligence.

The reason behind it is simple: I like being able to derive how a method works.

Classical algorithms link back to mathematics, and you can derive and conceptualize them. For example, depth from a rectified stereo pair follows from similar triangles:

> **Z = f · B / d**
>
> where *Z* is depth, *f* is focal length (in pixels), *B* is the baseline and *d* is disparity.

From this you can also predict how the error grows with distance:

> **δZ ≈ (Z² / (f · B)) · δd**

Machine learning is harder to reason about this way. The training procedure (backpropagation, optimization) is mathematics, but the learned function itself can't be written down or derived, so its inner workings and failure cases are harder to know in advance.

## Where ML fits

Regardless, I'm still interested in ML and in where it can perform better than classical methods in CV.
