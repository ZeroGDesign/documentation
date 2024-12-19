---
description: Which parts do you NEED to print to get started?
---

# Printing

## <mark style="color:red;">Measuring parts</mark>

We're going to measure some parts to make sure you've got the correct files to print. This is highly important to make sure pulleys and idlers move smoothly.

### <mark style="color:red;">Measure your toothed idler</mark>

We support several types of toothed idlers. To find the correct spacers, measure your idler’s height and check the next page for the corresponding spacers.

<figure><img src="../../../.gitbook/assets/toothed_idler_merc_measure.png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Find your spacer</mark>

Print the matching spacer to your idler’s height. Each spacer has one (1) dot[^1] for 8.5mm, two (2) for 9mm, and three (3) for 10mm.

The Configurator should include the correct file for you, but we’ve also included direct links below.

{% hint style="info" %}
Once measured, the tabs below will tell you what the printed spacer should look like, if it's hard to see click the image to enlarge it.
{% endhint %}

<details>

<summary><strong>10mm</strong></summary>

**You measured 10mm**

[a\_Xjoint\_10mm\_Idler\_Spacers.stl](https://github.com/ZeroGDesign/docs/blob/gh-pages/docs/assets/stl/m1_1/a_Xjoint_10mm_Idler_Spacers.stl)

Here is an example of the printed spacer you need

<img src="../../../.gitbook/assets/merc_spacer_10mm.png" alt="" data-size="original">

</details>

<details>

<summary><strong>9mm</strong></summary>

**You measured 9mm**

[a\_Xjoint\_9mm\_Idler\_Spacers.stl](https://github.com/ZeroGDesign/docs/blob/gh-pages/docs/assets/stl/m1_1/a_Xjoint_9mm_Idler_Spacers.stl)\
Here is an example of the printed spacer you need

<img src="../../../.gitbook/assets/merc_spacer_9mm.png" alt="" data-size="original">

</details>

<details>

<summary><strong>8.5mm</strong></summary>

**You measured 8.5mm**

[a\_Xjoint\_8mm\_Idler\_Spacers.stl](https://github.com/ZeroGDesign/docs/blob/gh-pages/docs/assets/stl/m1_1/a_Xjoint_8mm_Idler_Spacers.stl)

Here is an example of the printed spacer you need

<img src="../../../.gitbook/assets/merc_spacer_8mm.png" alt="" data-size="original">

</details>

## <mark style="color:red;">Recommended print settings</mark> <a href="#recommended-print-settings" id="recommended-print-settings"></a>

* First layer height: 0.25mm (This is required. Our parts have been designed for this.)
* Layer height: 0.2mm
* Extrusion width: 0.4mm, forced
* Infill percentage: 40%
* Infill type: Adaptive Cubic, grid, gyroid, honeycomb, triangle, or cubic
* Wall count: 4
* Solid top/bottom layers: 5
* Seam placement: **REAR**
  * This is important as we have seam relieve features that line up with the seam placement.
* Supports: NONE

{% hint style="info" %}
Over-extrusion leads to top layers with an inconsistent finish and/or blobbing. Check the top surfaces on the stepper towers and X joints, as these are mating faces.

Light sanding with sandpaper can help remove rough surfaces and ensure a proper fit between parts.
{% endhint %}

## <mark style="color:red;">Concepts</mark>

### <mark style="color:red;">Printed part codes</mark>

Our parts have printed codes to aid assembly. A part code identifies:

1. If the part belongs on the **left (‘L’)** or **right (‘R’)** side of the printer; and
2. The **version** of the part.

<figure><img src="../../../.gitbook/assets/merc_naming_concept_example.png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Flange Stacks</mark>

Flange stacks (along with 5x30mm dowel pins) are used to create smooth idlers.

{% hint style="info" %}
Quality idlers, smooth and toothed, are key for your printer's performance. We use flange stacks throughout assembly.
{% endhint %}

Single flange stacks use

* [**three (3)** shims](#user-content-fn-2)[^2] and [**two (2)** bearings](#user-content-fn-3)[^3].

Double stacks uses

* [**five (5**) shims](#user-content-fn-4)[^4] and [**four (4)** bearings](#user-content-fn-5)[^5].

<figure><img src="../../../.gitbook/assets/flange_stack_example_concept.png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Types of Idlers</mark>

#### <mark style="color:red;">Smooth Idlers</mark>

[Smooth idlers](#user-content-fn-6)[^6] are the most common idler that we will use; they turn the belt around its smooth side.

A **single flange stack** has **one (1)** smooth idler; a **double flange stack** has **two (2)**.

<figure><img src="../../../.gitbook/assets/smooth_idlers_flangestack_example.png" alt=""><figcaption></figcaption></figure>

#### <mark style="color:red;">Toothed Idlers</mark>

**Toothed idlers** are used on the **X joints only**. These are used when the belt turns towards its toothed side.

<figure><img src="../../../.gitbook/assets/toothed_idler_example.png" alt="" width="375"><figcaption></figcaption></figure>



[^1]: The printed spacers include a small dot in the bottom that'll tell you the size so you don't lose track.

[^2]: M5X1MM

[^3]: F695 BEARING

[^4]: M5X1MM

[^5]: F695 BEARING

[^6]: Revering to one step up, this is our definition of Smooth Idlers.
