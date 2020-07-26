# Fletcher-checksum
Implementation of fletcher checksum using python
1)Fletcher checksum is an error – detection technique that uses two checksums to determine single-bit errors in a message transmitted over network channels.
2)The checksums are created based on the data values in the data blocks to be transmitted and appended to the data. When the receiver gets this data, the checksums are re-calculated and compared with the existing checksums. A non-match indicates an error.
3)This implementation consists of Fletcher-16 and Fletcher-32 checksum. When a message is sent from the sender to receiver, the message may be received accurately or errors may be introduced. This code handles both possibilities.
