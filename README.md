# Image to ASCII Art (Python)

This is a simple Python script that converts an image into **ASCII art** using characters like `@`, `#`, `S`, `%`, etc.

It reads an image, turns it into grayscale, maps each pixel to an ASCII character based on brightness, and prints it as text. It also saves the output to a `.txt` file.

---

##  Requirements

- Python 3.x
- [Pillow](https://pypi.org/project/Pillow/)

Install Pillow:

```bash
pip install pillow
```

---

##How to Use

1. Clone the repo or copy the script.
2. Run the script:

```bash
python image_to_ascii.py
```

3. Enter the path to your image file when asked:

```
Enter a valid pathname to an image:
myimage.jpg
```

4. ASCII art will be printed in the terminal and saved to `ascii_image.txt`.

---

##  How It Works

- Resizes the image to fit your terminal.
- Converts it to grayscale.
- Maps pixel brightness to characters from a list.
- Builds a text representation of the image using those characters.

---

##  Output Example

```text
@#S%%**++:;
@#S%%**++:;
....
```

---

## 📄 License

Free to use under the MIT License.
