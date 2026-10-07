# Hi, I'm Chris

Welcome to my GitHub profile!

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
