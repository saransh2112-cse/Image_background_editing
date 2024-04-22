# Change Background Image Tool

This tool allows you to change the background of images using a given set of foreground images and background images.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/saransh2112-cse/Image_background_editing.git
```

2. Navigate to the project directory:

```bash
cd change-background-image-tool
```

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Place your foreground images in the `input_images` folder.
2. Place your background images in the `background_images` folder.
3. Run the script `change_background.py`:

```bash
python change_background.py
```

4. The script will generate new images with the background changed and save them in the `output_images` folder.

## Approach

1. The script reads each foreground image from the `input_images` folder.
2. It then reads each background image from the `background_images` folder.
3. For each combination of a foreground image and a background image, it changes the background using the provided algorithm.
4. The resulting images are saved in the `output_images` folder with filenames indicating the original foreground image and background image.

## Dependencies

- OpenCV (cv2)
- NumPy
- Matplotlib
