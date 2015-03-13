SOURCE FOR "FPGAs?! Now What?" TEXT.
    These are the source files for the text "FPGAs?! Now What?", a book
    about FPGA design using Xilinx ISE WebPACK and the XuLA FPGA board.

SOURCE FILE ORGANIZATION
    The source files for the book are organized as follows:

        FpgasNowWhat:                        // Top-level directory
            Example_code.zip                 // VHDL code used throuhout the book
            FpgasNowWhatBook.odm             // Master book file that incorporates material from all the subdirectories.
            Chapters:                        // Subdirectory containing the source for each chapter.
                FirstFpgaDownload:           // Subdirectory containing the source files for this chapter.
                    FirstFpgaDownload.odt    // Chapter text (OpenOffice/LibreOffice Writer file).
                    Figures:                 // Subdirectory containing figure graphics source files.
                        *.svg                // Inkscape files for figures. (Not used directly in text.)
                        *.png                // Bitmaps of Inkscape files. (For inclusion in text.)
                    FPGA:                    // Subdirectory containing FPGA project examples for this chapter.
                        blinker:             // Subdirectory of Xilinx ISE 13 project files.
                            blinker.xise     // Xilinx ISE 13 project file.
                            ...              // The rest of the project files.
                    Videos:                  // Subdirectory containing video clips.
                        blinker_0001.mp4     // Video of blinker operation.
                Compiler Basics:             // Same subdirectory structure for this chapter.
                    ...
                FirstFpgaDesign:             // Same subdirectory structure for this chapter.
                    ...
                ...                          // Additional chapters.

TOOLS
    All the text is in .odt files written using LibreOffice/OpenOffice
    Writer. All the figures are .svg files created with Inkscape. All the
    images are .png files captured with various tools. All the videos are
    .mp4 files.

AUTHOR
    Dave Vanden Bout, X Engineering Software Systems Corp, devb@xess.com.

COPYRIGHT AND LICENSES
    Copyright 2011 - X Engineering Software Systems Corp. (www.xess.com)

  Book License
    All text, graphics and video for this book are licensed under a Creative
    Commons Attribution-ShareAlike 3.0 Unported License
    (http://creativecommons.org/licenses/by-sa/3.0/).

  Software License
    All FPGA project files, scripts and program code are licensed under a
    GPL license as follows:

    This program is free software; you can redistribute it and/or modify it
    under the terms of the GNU General Public License as published by the
    Free Software Foundation; either version 2 of the License, or (at your
    option) any later version.

    This program is distributed in the hope that it will be useful, but
    WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
    Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    59 Temple Place - Suite 330, Boston, MA 02111-1307, USA.
