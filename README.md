# M&M Image Analysis

This Jupyter Notebook (`code.ipynb`) analyzes images to detect and count the number of M&M candies of various colors, including blue, red, green, yellow, orange, and brown. It uses computer vision techniques and OpenCV to process the images and identify M&Ms of different colors.

## Prerequisites

Before running the Jupyter Notebook, make sure you have the following Python libraries installed:

- NumPy
- OpenCV (cv2)
- Matplotlib
- PrettyTable
- pathlib

You can install these libraries using the following command:

```cmd
pip install numpy opencv-python-headless matplotlib prettytable
```

## Usage

1. Clone the repository to your local machine:

```cmd
git clone https://github.com/Merve-1/Finding-Counting-M-Ms.git
```

2. Place the images you want to analyze in the `images` directory.

3. Open the Jupyter Notebook:

```cmd
jupyter notebook code.ipynb
```

4. Run the notebook cell by cell to process the images. The notebook will display the results, including the total count of M&Ms and the count of M&Ms for each color.

## Example Output

Here's an example of the output you can expect:

```
+------------+---------------+----------------+---------------+-----------------+------------------+------------------+-----------------+
| Image Name | # of all m&ms | # of blue m&ms | # of red m&ms | # of green m&ms | # of yellow m&ms | # of orange m&ms | # of brown m&ms |
+------------+---------------+----------------+---------------+-----------------+------------------+------------------+-----------------+
|     0      |       55      |       12       |       5       |        12       |        11        |        9         |        6        |
|     1      |       55      |       12       |       5       |        12       |        11        |        9         |        6        |
...
```

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request. Your contributions are welcome!


## Acknowledgments

- This project uses the [OpenCV](https://opencv.org/) library for image processing.

