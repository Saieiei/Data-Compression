# Enhancing Data Compression: A Dynamic Programming Approach with Huffman Coding and Burrows-Wheeler Transform

Overview
This project explores a novel data compression method that combines Huffman coding and Burrows-Wheeler Transform (BWT) to enhance image compression. By leveraging these advanced algorithms, the project demonstrates significant improvements in compression ratios compared to using these techniques individually. Additionally, dynamic programming techniques are applied to optimize the algorithm's efficiency.

Features
Huffman Coding: A lossless data compression technique that assigns shorter codes to frequently occurring symbols, reducing the size of image files without losing quality.
Burrows-Wheeler Transform (BWT): Reorganizes data to make it more suitable for compression, leading to better compression efficiency when used with Huffman coding.
Dynamic Programming: Enhances the overall efficiency of the combined compression algorithm, making it suitable for real-world applications.

How It Works
Data Gathering: A variety of images with different resolutions and color depths are used to test the compression algorithms.
Algorithm Implementation: The algorithms are implemented in Python, utilizing the Python Imaging Library (PIL) for image processing.
Image Compression: Both Huffman and BWT algorithms are applied to the images, and their compression ratios are compared.
Quality Evaluation: The quality of the compressed images is assessed using Peak Signal to Noise Ratio (PSNR) and Structural Similarity Index (SSIM).
Result Comparison: The performance of the algorithms is analyzed based on compression ratios, PSNR, and SSIM values.

Results
Huffman Compression: Achieved a compression size of 834,899 bits with a compression factor of 1.004.
BWT Compression: Achieved a compression size of 838,648 bits with a compression factor of 1.0.
Combined Huffman + BWT Compression: Achieved a significantly smaller compression size of 37,812 bits with a compression factor of 22.179.

Conclusion
The project demonstrates that combining Huffman coding with BWT, along with dynamic programming, leads to highly efficient image compression. This approach is particularly effective for reducing the storage and transmission requirements of large images, making it a valuable technique for various applications, including medical imaging, remote sensing, and more.
