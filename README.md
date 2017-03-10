Rust implementation of ISO6937 Codec
====================================

Implementation is rough and clearly not very efficient but should work fine.

New line characters are coded as 0x85 which is a special character that is not
part of the standard. This can be seen as an extension used in the EBU-STL
subtitle format.
