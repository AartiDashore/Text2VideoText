# Text to Text Video Converter

This Python program converts text input from a file into an equivalent video. Each frame of the video represents a portion of the text, creating a dynamic visual representation of the text content.

## Requirements

- Python 3.x
- OpenCV
- MoviePy

## Installation

You can install the required libraries using pip:

```bash
pip install opencv-python moviepy
```

## Usage

1. Ensure you have a text file (`input.txt`) with the content you want to convert into a video.
2. Run the Python script `Text2TypedVideo.ipynb`.
3. After execution, the script will generate a video file named `output.mp4` containing the visualization of the text content.

```bash
python text_to_video.py
```

## Customization

- Modify the `input.txt` file to change the text content you want to visualize.
- Adjust parameters such as frame rate, text size, and font in the `Text2TypedVideo.ipynb` script to customize the output video.

## Example

Suppose you have a text file `input.txt` with the following content:

![1](https://github.com/AartiDashore/Text2VideoText/assets/38726886/4ef3667f-11c3-4b71-8152-5544f0c7b61e)



Running the script will generate a video `output.mp4` where each frame displays an incrementally growing portion of the text.



https://github.com/AartiDashore/Text2VideoText/assets/38726886/476b7387-62a2-48f9-b744-d0c10922a6f2


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
