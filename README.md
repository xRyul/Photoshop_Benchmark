# Photoshop Speed Benchmark
Small Benchmark for Photoshop 🚀

![Photoshop_speed_benchmark_example](https://user-images.githubusercontent.com/47340038/179255250-5907925f-b439-4abf-82a5-e293b53fada9.gif)

Benchmark to check execution time of the following:
- Opening Image
- Converting to Smart Object,
- Select Subject
- Crop
- Resizing image to 10000pixels on the longest edge with "Preserve Details 2.0" 
- Canvas Resize
- Content Aware Fill.. (which you access through the menu, not SHIFT+F5)

## Why
If you use Photoshop in a busy fast paced photostudio environment, you will know that every second counts. 

Most of the other benchmarks focus on the final **TOTAL SCORE**. Which is great for knowing how much performance your machine can get out of Photoshop. But what if you only care about resizing the images, but not about Gausian Blur, what if you only work in 8bit and not 16bit, what if you only use Quick Select, but not Select Subject; small brush, but not the large bursh; clone stamp tool, but not the healing brush etc. Knowing the total score doesn't give any options to optimize Photoshop performance towards your personal needs. That is why it is always better to know the performance and speed of each individual task. 

- Useful for when trying to get the peak performance out of your machine and the Photosho. 
- Checking how modification of various "_Performance_" settings (e.g. Cache Levels, Tile Sizes, Advanvced Graphics Processor settings etc. ), affects the speed of the photoshop. 
- Checking how turning on and off any background processes affects the performance of the Photoshop. 
- For comparing PC and MAC builds

Most of these are super simple functions. But which are comonly used by such e-commerce Photostudios as Selfridges, TK Maxx, Debenhmas, Topshop, Next and many more. 

Most of the commands are taken from https://github.com/Adobe-CEP/CEP-Resources/tree/master/Documentation/Product%20specific%20Documentation/Photoshop%20Scripting

Except **Image Resize** with Preserve Detail 2.0 and **Content Aware Fill** which needed to be scripted through the Script Listener. 


# 🕹 To use
1. Open terminal and cd into the Desktop `cd ~/Desktop/`
2. Clone the repo `git clone https://github.com/xRyul/Photoshop_Benchmark.git`
3. Open **Photoshop**
4. Locate  the benchmark script "_~/Desktop/Photoshop_Speed_Benchmark/Photoshoo_Benchmark.jsx_" and simply drag and drop it into the **Photoshop**
5. If promtped for confirmation, click `OK` to run the script.

**It takes between 40s-2min to execute. The most important numbers to lookout for would be from Select Subject, Image Resize, and Content Aware Fill.**

---
# 🏁 Example results:
### M1 Pro 32gb 1TB - PS 24.1
![M1 Pro 32gb 1TB (Custom)](https://user-images.githubusercontent.com/47340038/179262740-1a10be93-4a71-4382-a16b-6ee2541000c0.jpg)

### Ryzen 3950x - Samsung 980 Pro 1TB - Ps 23.2
![Ryzen 3950x](https://user-images.githubusercontent.com/47340038/179261960-3718cb7a-0c79-40bd-94fa-13164cfe82cf.jpg)

### Ryzen 2700x - PS 23.2
![Ryzen 2700x_PS23_2](https://user-images.githubusercontent.com/47340038/179260549-52c4a87f-d89b-4c0d-837f-11698eef134e.jpg)

### Ryzen 2700x - PS 24.1
![Ryzen 2700x_PS23_2_23 4 1](https://user-images.githubusercontent.com/47340038/179260612-391e714a-5773-466a-a17b-259d94929e6c.jpg)





 
