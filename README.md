# Recursive Inscriptions

## What is a Recursive Inscription?

A recursive inscription links one ordinal inscription to another, making them compose-able. For example, a composite image can be made up of multiple layers, or a section of code can be linked together in the correct order, like a piece of music.

## Why Would You Want to Make One?

Two reasons you may want to create recursive inscriptions:
1. **Save network fees** on the cost of minting copies of large composite images.
2. **Link together code, images, or other media** that is too large in data size to fit into one inscription.

### Excerpt from Our Resource for Inspiration

> "With this new update, inscriptions can become very powerful and inherit elements from previous inscriptions. For example, someone could inscribe popular Javascript and CSS libraries for anyone to use, allowing rich HTML files to be inscribed directly on Bitcoin and even link to each other."

## What Types of Files Are Supported for Inscribing?

I found this guide and am assuming that ordinalsbot supports similar file types: [Gamma Supported File Types](https://support.gamma.io/hc/en-us/articles/13772220095891-What-file-types-are-supported-for-ordinal-inscription-images-on-Gamma#heading-3)

Also note, although not listed in Ordinalsbot supported file types, I was able to upoad the index.html.  I don't know if ordinalsbot will support uploading JavaScript.

**Resource**: [Ordinalsbot Recursive Inscriptions Article](https://ordinalsbot.medium.com/recursive-inscriptions-creating-a-collection-from-shared-layers-b43a628144e8)

## Testing Plan

Attempt to use [ordinalsbot](https://ordinalsbot.com/) to layer these images on top of each other to create a composite image.

### Layers:

- [**Layer 1**](https://ord.xverse.app/inscription/91140707cd95804a2be7baa30466ed3f29a33ee91010fadb08334f92a2b6c0dfi0)
- [**Layer 2**](https://ord.xverse.app/inscription/b34f672acc80c2166ed719041a08fd1cce9e1ab09d7b61665d03ed65f34c0c80i0)
- [**Layer 3**](https://ord.xverse.app/inscription/ca33b0760d861d06e5323b8ac09b24a2da3d34eeeaeaf350c2b5a678c6c25fc3i0)
- [Recursive Inscription that stitches all these together](https://ord.xverse.app/inscription/bcf0f027b4332b295e48597f8ad717309d6b27ef44bd4f255d5c9c0ed34ad453i0)

## Testing Detailed Notes

- **Wallet Used**: [Xverse Browser Wallet](https://www.xverse.app/download)
- **Tool for Inscription**: [Ordinalsbot](https://ordinalsbot.com/)


### Transaction IDs

- [Transaction 1](https://mempool.space/tx/91140707cd95804a2be7baa30466ed3f29a33ee91010fadb08334f92a2b6c0df)
- [Transaction 2](https://mempool.space/tx/b34f672acc80c2166ed719041a08fd1cce9e1ab09d7b61665d03ed65f34c0c80)
- [Transaction 3](https://mempool.space/tx/b34f672acc80c2166ed719041a08fd1cce9e1ab09d7b61665d03ed65f34c0c80)
- [Recursive Inscription Transaction](https://mempool.space/es/tx/bcf0f027b4332b295e48597f8ad717309d6b27ef44bd4f255d5c9c0ed34ad453)
**Only 317 vB!**

## To DIY this

1. Modify the index.html file and index.json file to match the inscriptions you would like to stack.
2. Submit the `index.html` and `index.json` in ordinals bot.

5. When complete, [here's an example stacking](https://ord.xverse.app/inscription/bcf0f027b4332b295e48597f8ad717309d6b27ef44bd4f255d5c9c0ed34ad453i0)
 three image layers (background, circuit, key and some scratch metadata.)