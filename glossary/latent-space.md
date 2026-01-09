## Latent Space

**Latent Space** is the mathematical foundation of every Large Language Model. 
During training, a Transformer model converts the *tokens* (roughly corresponding to words or parts of words) discovered in billions of documents into *embeddings*. 
These are sequences of numbers — *vectors* — that define the semantic distance between concepts.

We are dealing with Linear Algebra. In large models, this space often consists of several thousand dimensions. 
This is not something a human can visualize spatially; I advise *against* the attempt, as it leads only to a headache. 
It is more productive to conceive of it as an **extremely dense map** — a topology of extracted concepts — rather than a multidimensional body.

When you prompt an AI, it “moves” through this space to calculate the statistically optimal response. 
While we will examine the mechanics of this movement in later posts, several points are vital to understand now:

* **An Archive, Not an Oracle:** The Latent Space is not a realm of absolute truth or a “collective consciousness.” It is an archive of human utterances. It is composed only of what has already been thought and expressed. Consequently, it is riddled with *bias*. If historical sources underrepresent certain demographics, the Latent Space will do the same. This is not a “bug” in the architecture; it is a property of the sources. It is “Latent Time”. Criticizing a model for reflecting historical bias is like entering a city archive and complaining that the lists of mayors from the 1800s lack diversity. It is a mirror — often a distorted one — of our own record.
* **The Familiar Alien [1]:** While the Latent Space is pure mathematics, it is deeply human because it feeds on human output. The AI’s “cognition” is orthogonal to ours. It is strange, yet not extraterrestrial.
* **The Weight of Superposition:** AI “thinks” topologically, not temporally. Information exists simultaneously and is often *superpositioned* (overlapping). For the humanities, this is critical: 19th-century scholarship exists alongside 21st-century breakthroughs. Without guidance, the AI struggles to resolve these superpositions in favor of the present because the “weight” of the past is so immense.
* **Plausibility over Truth:** AI prioritizes statistical probability. It masters logic to an extent but excels at plausibility. That authority is purely male, for instance, is factually false but historically “plausible” within the training data. Plausibility is not truth.

---
[1] Uwo Hölscher coined the term “das nächste Fremde” to describe the simultaneous proximity and strangeness of Antiquity relative to the present. While often translated as “the nearest stranger,” I have chosen “familiar alien” to avoid the personification of the machine. The conceptual core remains the same: the AI is familiar yet fundamentally different — orthogonal, but not opposite.
