---
layout: default
modal-id: 5
date: 2014-07-14
img: fpga.png
alt: image-alt
project-date: June 2017
<!-- client: Start Bootstrap -->
category: FPGA; Pipelining;
description: This project utilises the parallel processing capabilities of the Zybo Zynq-7000 <strong>FPGA</strong> to perform phrase detection from an input video feed at 120 Frames Per Second (FPS). The use of Vivdao High Level Synthesis(HLS) meant that algorithms can be expressed in a more familiar language - C. Despite that, algorithms must be expressed in a non-traditional way to allow for efficient hardware synthesis in the FPGA. This required an understanding of how C constructs are mapped to physical hardware.</br></br> The use of a <strong>double buffering</strong> technique enabled the system to perform <strong>non-sequential data manipulation</strong> which is not immediately possible in a pipelined architecture. This allowed for a high throughput and hence a frame rate of 120 FPS.</br></br>This was a particularly interesting project as it forces one to rethink algorithm design in order to exploit the parallelism which an FPGA offers. This project was awarded <strong>Best First Year Project</strong>. 

---
