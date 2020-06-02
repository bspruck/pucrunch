The current compressor can compress/decompress files for C64 (-c64), VIC20 (-c20), C16/+4 (-c16), or for standalone decompressor (-c0).

As of 21.12.2005 Pucrunch is under GNU LGPL: See http://creativecommons.org/licenses/LGPL/2.1/ or http://www.gnu.org/copyleft/lesser.html.

The decompression code is distributed under the WXWindows Library Licence: See http://www.wxwidgets.org/licence3.txt. (In short: binary version of the decompression code can accompany the compressed data or used in decompression programs.) 

Remarks for the Lynx version:
The packer code includes a small patch to detect lynx executeables and read their header information.
This breaks support for C64... files. Which I dont care about.
The decompressor code is missing any check for the file format. The file have to be "converted" on cartridge building and the directory has to be filled accordingly (by lynxdir for example).
24.12.2011 Björn Spruck
