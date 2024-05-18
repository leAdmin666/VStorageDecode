## Usage

The decode functionality of the `vstorage` program extracts data from an encoded image file. The general usage is as follows:

```sh
vstorage --decode <File>
```

### Parameters

- `--decode`: This flag indicates that you want to decode an image file.
- `<File>`: This is the path to the image file that you want to decode.

### Example

To decode an image file named `encoded_image.png`, use the following command:

```sh
vstorage --decode encoded_image.png
```

### Detailed Steps

1. **Run the Decode Command:** Execute the `vstorage` program with the `--decode` flag followed by the path to the image file you want to decode.

```sh
vstorage --decode encoded_image.png
```


2. **Decoding Process:** The program will begin decoding the specified image file. You will see a progress bar indicating the decoding progress.

3. **Output:** Once the decoding is complete, the program will create a file with the extracted data. The name of the output file is derived from the encoded data within the image.

4. **Completion Message:** Upon successful creation of the output file, the program will display a message indicating the name of the created file.

### Error Handling

- If no arguments are provided, the program will display an error message and usage instructions.
- If the specified file does not exist or cannot be loaded, the program will display an appropriate error message.
- If the program encounters any issues during the decoding process, it will display an error message and terminate.

### Example Output

```sh
Decoding...
[==================================================>] 100 %
File: extracted_data.txt was successfully created.
```

This output indicates that the decoding process was successful and the extracted data was saved to `extracted_data.txt`.

## Notes

- Ensure that the image file you are trying to decode was previously encoded using the `vstorage` program. The program looks for specific markers and encoded data formats, and attempting to decode a regular image file will result in errors.

--------------------------------------------------------------------------

By following this guide, you should be able to successfully use the decode functionality of the `vstorage` program. If you encounter any issues or have further questions, feel free to reach out or open an issue on the project's GitHub repository.

--------------------------------------------------------------------------
