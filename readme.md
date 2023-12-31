# Eye Message Tests

Various tests with the Eye messages, notorious secret messages found in the game Noita which are yet to be decyphered. This is my attempt at helping the community solve the messages.

## Test1 - Horizontal Trigrams

This produces base-10 values between 0 and 84 with no gaps, and occasional double letters.

You can view a more detailed analysis here:
https://docs.google.com/spreadsheets/d/1XbB7UssF_DyaaVAWYnmK65PwchKbcXnl_lOBaBFOPw4/edit?usp=sharing

Here is the output of the python script:

```
[EAST 1]
---------------
New reading order:
[2, 0, 1, 0, 1, 3, 2, 2, 3, 3, 0, 4, 0, 4, 1, 1, 3, 0, 2, 3, 2, 1, 1, 4, 3, 1, 3, 0, 3, 3, 0, 0, 4, 0, 2, 4, 0, 0, 0, 
 3, 1, 1, 1, 4, 3, 1, 0, 2, 3, 0, 0, 0, 1, 1, 0, 2, 2, 2, 2, 1, 2, 4, 2, 2, 2, 4, 1, 0, 0, 0, 2, 2, 1, 4, 0, 2, 3, 0, 
 3, 1, 0, 2, 2, 1, 0, 4, 4, 0, 0, 0, 2, 0, 0, 1, 0, 4, 0, 4, 0, 1, 4, 4, 1, 4, 2, 0, 3, 3, 0, 2, 2, 0, 3, 4, 2, 4, 1, 
 1, 1, 2, 1, 4, 4, 1, 4, 3, 1, 4, 4, 1, 3, 3, 1, 3, 2, 2, 4, 1, 0, 2, 1, 2, 3, 1, 1, 3, 0, 0, 3, 1, 3, 1, 3, 1, 3, 2, 
 0, 1, 4, 0, 0, 3, 2, 1, 2, 1, 1, 4, 1, 3, 0, 0, 4, 1, 1, 1, 0, 1, 0, 0, 2, 4, 1, 2, 4, 1, 0, 0, 4, 0, 3, 1, 0, 0, 1, 
 2, 0, 4, 2, 4, 4, 2, 4, 4, 2, 1, 4, 0, 2, 1, 0, 4, 0, 0, 1, 0, 1, 0, 1, 2, 2, 1, 1, 4, 3, 2, 3, 4, 1, 3, 3, 0, 4, 0, 
 1, 3, 3, 3, 1, 2, 2, 0, 3, 3, 0, 1, 0, 3, 1, 1, 3, 1, 1, 1, 2, 1, 1, 2, 1, 0, 3, 2, 2, 3, 1, 4, 3, 1, 3, 4, 0, 2, 3, 
 2, 1, 3, 0, 2, 0, 1, 1, 4, 0, 3, 0, 3, 1, 4, 2, 2, 4, 2, 4, 0, 1, 3, 1]

Tri:
['201', '013', '223', '304', '041', '130', '232', '114', '313', '033', '004', '024', '000', 
 '311', '143', '102', '300', '011', '022', '221', '242', '224', '100', '022', '140', '230', 
 '310', '221', '044', '000', '200', '104', '040', '144', '142', '033', '022', '034', '241', 
 '112', '144', '143', '144', '133', '132', '241', '021', '231', '130', '031', '313', '132', 
 '014', '003', '212', '114', '130', '041', '110', '100', '241', '241', '004', '031', '001', 
 '204', '244', '244', '214', '021', '040', '010', '101', '221', '143', '234', '133', '040', 
 '133', '312', '203', '301', '031', '131', '112', '112', '103', '223', '143', '134', '023', 
 '213', '020', '114', '030', '314', '224', '240', '131']

Base 10:
[51,  8, 63, 79, 21, 40, 67, 34, 83, 18,  4, 14,  0, 
 81, 48, 27, 75,  6, 12, 61, 72, 64, 25, 12, 45, 65, 
 80, 61, 24,  0, 50, 29, 20, 49, 47, 18, 12, 19, 71, 
 32, 49, 48, 49, 43, 42, 71, 11, 66, 40, 16, 83, 42, 
  9,  3, 57, 34, 40, 21, 30, 25, 71, 71,  4, 16,  1, 
 54, 74, 74, 59, 11, 20,  5, 26, 61, 48, 69, 43, 20, 
 43, 82, 53, 76, 16, 41, 32, 32, 28, 63, 48, 44, 13, 
 58, 10, 34, 15, 84, 64, 70, 41]
---------------

[WEST 1]
---------------
New reading order:
[3, 1, 1, 0, 1, 3, 2, 2, 3, 3, 0, 4, 0, 4, 1, 1, 3, 0, 2, 3, 2, 1, 1, 4, 3, 1, 3, 0, 3, 3, 0, 0, 4, 0, 2, 4, 0, 0, 4, 
 1, 0, 1, 1, 4, 3, 1, 0, 2, 3, 0, 0, 0, 1, 1, 0, 2, 2, 2, 2, 1, 2, 4, 2, 2, 2, 4, 1, 0, 0, 0, 2, 2, 1, 4, 0, 2, 3, 0, 
 0, 2, 0, 2, 0, 1, 0, 4, 4, 0, 0, 0, 1, 0, 4, 0, 4, 4, 0, 4, 0, 1, 4, 4, 1, 4, 2, 0, 3, 3, 0, 2, 2, 0, 3, 4, 1, 3, 1, 
 1, 0, 4, 1, 4, 4, 1, 4, 3, 1, 4, 4, 1, 3, 3, 1, 3, 2, 2, 4, 1, 0, 2, 0, 2, 0, 1, 1, 0, 0, 0, 3, 1, 3, 1, 2, 1, 1, 1, 
 2, 1, 2, 2, 2, 3, 3, 0, 3, 2, 4, 4, 0, 0, 0, 2, 4, 3, 2, 3, 1, 1, 1, 0, 2, 2, 1, 2, 3, 1, 0, 3, 1, 0, 2, 2, 0, 4, 3, 
 2, 3, 1, 0, 3, 3, 1, 2, 2, 1, 4, 3, 3, 1, 4, 1, 0, 3, 0, 1, 2, 0, 4, 3, 1, 1, 1, 2, 2, 2, 1, 0, 4, 1, 3, 4, 3, 0, 4, 
 0, 2, 4, 1, 4, 2, 2, 1, 4, 2, 2, 2, 0, 3, 0, 2, 4, 2, 0, 0, 1, 2, 3, 2, 1, 2, 4, 0, 2, 3, 2, 3, 2, 0, 1, 4, 0, 3, 3, 
 1, 1, 4, 2, 2, 3, 1, 3, 0, 1, 3, 2, 2, 4, 0, 0, 2, 2, 2, 2, 3, 0, 2, 0, 3, 1, 2, 1, 1, 2, 2, 3, 1, 0, 1, 3]

Tri:
['311', '013', '223', '304', '041', '130', '232', '114', '313', '033', '004', '024', '004', 
 '101', '143', '102', '300', '011', '022', '221', '242', '224', '100', '022', '140', '230', 
 '020', '201', '044', '000', '104', '044', '040', '144', '142', '033', '022', '034', '131', 
 '104', '144', '143', '144', '133', '132', '241', '020', '201', '100', '031', '312', '111', 
 '212', '223', '303', '244', '000', '243', '231', '110', '221', '231', '031', '022', '043', 
 '231', '033', '122', '143', '314', '103', '012', '043', '111', '222', '104', '134', '304', 
 '024', '142', '214', '222', '030', '242', '001', '232', '124', '023', '232', '014', '033', 
 '114', '223', '130', '132', '240', '022', '223', '020', '312', '112', '231', '013']

Base 10:
[81,  8, 63, 79, 21, 40, 67, 34, 83, 18,  4, 14,  4, 
 26, 48, 27, 75,  6, 12, 61, 72, 64, 25, 12, 45, 65, 
 10, 51, 24,  0, 29, 24, 20, 49, 47, 18, 12, 19, 41, 
 29, 49, 48, 49, 43, 42, 71, 10, 51, 25, 16, 82, 31, 
 57, 63, 78, 74,  0, 73, 66, 30, 61, 66, 16, 12, 23, 
 66, 18, 37, 48, 84, 28,  7, 23, 31, 62, 29, 44, 79, 
 14, 47, 59, 62, 15, 72,  1, 67, 39, 13, 67,  9, 18, 
 34, 63, 40, 42, 70, 12, 63, 10, 82, 32, 66,  8]
---------------

[EAST 2]
---------------
New reading order:
[1, 2, 1, 0, 1, 3, 2, 2, 3, 3, 0, 4, 0, 4, 1, 1, 3, 0, 2, 3, 2, 1, 1, 4, 3, 1, 3, 0, 3, 3, 0, 0, 4, 
 0, 2, 4, 0, 0, 4, 2, 3, 1, 1, 4, 3, 1, 0, 2, 3, 0, 0, 0, 1, 1, 0, 2, 2, 2, 2, 1, 2, 4, 2, 2, 2, 4, 
 1, 0, 0, 0, 2, 2, 1, 4, 0, 2, 3, 1, 3, 0, 2, 0, 1, 3, 2, 3, 0, 0, 4, 4, 2, 1, 0, 1, 4, 3, 0, 0, 1, 
 2, 1, 4, 1, 4, 0, 3, 1, 1, 0, 2, 4, 1, 0, 4, 2, 2, 3, 2, 2, 4, 1, 4, 4, 2, 2, 3, 0, 1, 0, 1, 3, 2, 
 0, 3, 1, 0, 3, 3, 3, 0, 4, 1, 3, 2, 2, 2, 2, 3, 1, 1, 1, 4, 4, 2, 0, 1, 0, 1, 4, 1, 1, 3, 0, 3, 0, 
 1, 4, 4, 1, 0, 2, 0, 2, 0, 3, 1, 1, 1, 1, 4, 2, 4, 1, 0, 3, 4, 2, 3, 2, 1, 3, 2, 1, 1, 2, 0, 4, 0, 
 1, 2, 2, 3, 0, 1, 0, 0, 0, 0, 4, 0, 2, 0, 4, 2, 2, 1, 2, 2, 0, 3, 0, 1, 0, 4, 0, 0, 2, 1, 0, 2, 1, 
 1, 4, 1, 0, 0, 1, 1, 3, 2, 2, 1, 0, 0, 4, 2, 2, 3, 1, 0, 4, 3, 2, 4, 2, 0, 1, 3, 1, 0, 3, 0, 1, 0, 
 2, 0, 0, 3, 0, 0, 2, 2, 1, 2, 2, 4, 1, 0, 2, 1, 4, 4, 0, 1, 3, 3, 0, 1, 0, 0, 0, 1, 3, 2, 0, 3, 3, 
 1, 3, 0, 2, 1, 3, 0, 4, 2, 2, 4, 1, 0, 2, 0, 0, 3, 4, 2, 0, 1, 0, 4, 3, 1, 0, 1, 1, 0, 0, 2, 0, 0, 
 1, 2, 4, 1, 1, 3, 2, 2, 3, 1, 4, 1, 0, 2, 0, 2, 2, 0, 2, 0, 4, 1, 3, 1]

Tri:
['121', '013', '223', '304', '041', '130', '232', '114', '313', '033', '004', 
 '024', '004', '231', '143', '102', '300', '011', '022', '221', '242', '224', 
 '100', '022', '140', '231', '302', '013', '230', '044', '210', '143', '001', 
 '214', '140', '311', '024', '104', '223', '224', '144', '223', '010', '132', 
 '031', '033', '304', '132', '222', '311', '144', '201', '014', '113', '030', 
 '144', '102', '020', '311', '114', '241', '034', '232', '132', '112', '040', 
 '122', '301', '000', '040', '204', '221', '220', '301', '040', '021', '021', 
 '141', '001', '132', '210', '042', '231', '043', '242', '013', '103', '010', 
 '200', '300', '221', '224', '102', '144', '013', '301', '000', '132', '033', 
 '130', '213', '042', '241', '020', '034', '201', '043', '101', '100', '200', 
 '124', '113', '223', '141', '020', '220', '204', '131']

Base 10:
[36,  8, 63, 79, 21, 40, 67, 34, 83, 18,  4, 14,  4, 
 66, 48, 27, 75,  6, 12, 61, 72, 64, 25, 12, 45, 66, 
 77,  8, 65, 24, 55, 48,  1, 59, 45, 81, 14, 29, 63, 
 64, 49, 63,  5, 42, 16, 18, 79, 42, 62, 81, 49, 51, 
  9, 33, 15, 49, 27, 10, 81, 34, 71, 19, 67, 42, 32, 
 20, 37, 76,  0, 20, 54, 61, 60, 76, 20, 11, 11, 46, 
  1, 42, 55, 22, 66, 23, 72,  8, 28,  5, 50, 75, 61, 
 64, 27, 49,  8, 76,  0, 42, 18, 40, 58, 22, 71, 10, 
 19, 51, 23, 26, 25, 50, 39, 33, 63, 46, 10, 60, 54, 
 41]
---------------

[WEST 2]
---------------
New reading order:
[3, 0, 1, 0, 1, 4, 3, 0, 4, 2, 3, 1, 1, 1, 1, 1, 3, 0, 1, 0, 3, 2, 0, 0, 1, 1, 4, 2, 1, 1, 1, 4, 2, 0, 4, 2, 1, 4, 4, 
 2, 0, 4, 0, 2, 1, 0, 2, 2, 2, 2, 0, 0, 4, 2, 3, 1, 0, 1, 4, 1, 2, 2, 2, 0, 0, 2, 1, 4, 4, 2, 0, 0, 1, 4, 0, 2, 3, 1, 
 1, 1, 0, 1, 2, 0, 2, 1, 0, 0, 4, 4, 0, 1, 2, 0, 2, 2, 0, 1, 4, 1, 0, 0, 2, 0, 2, 1, 3, 0, 0, 1, 3, 2, 4, 3, 3, 1, 2, 
 3, 0, 0, 0, 0, 1, 1, 3, 0, 3, 1, 2, 3, 1, 3, 2, 2, 4, 1, 3, 4, 3, 1, 3, 2, 2, 3, 0, 1, 0, 2, 1, 1, 0, 3, 1, 1, 0, 4, 
 1, 4, 3, 1, 1, 0, 2, 2, 3, 0, 2, 4, 2, 2, 4, 2, 0, 1, 0, 2, 1, 2, 2, 3, 1, 4, 2, 2, 0, 0, 1, 0, 3, 1, 1, 1, 2, 2, 3, 
 0, 4, 4, 1, 1, 2, 0, 4, 1, 2, 4, 2, 0, 3, 2, 0, 2, 2, 2, 3, 1, 3, 1, 2, 2, 2, 2, 1, 4, 0, 0, 3, 2, 1, 0, 4, 3, 0, 2, 
 1, 2, 2, 2, 0, 1, 0, 0, 0, 0, 1, 2, 1, 4, 3, 1, 0, 1, 2, 3, 3, 3, 1, 2, 0, 1, 0, 2, 2, 4, 2, 0, 3, 2, 2, 1, 0, 3, 0, 
 2, 2, 3, 0, 2, 3, 1, 4, 2, 0, 3, 0, 2, 3, 0, 3, 0, 1, 1, 3, 2, 1, 2, 3, 1, 0, 1, 0, 1, 0, 1, 1, 0]

Tri:
['301', '014', '304', '231', '111', '130', '103', '200', '114', '211', '142', '042', '144', 
 '204', '021', '022', '220', '042', '310', '141', '222', '002', '144', '200', '140', '231', 
 '110', '120', '210', '044', '012', '022', '014', '100', '202', '130', '013', '243', '312', 
 '300', '001', '130', '312', '313', '224', '134', '313', '223', '010', '211', '031', '104', 
 '143', '110', '223', '024', '224', '201', '021', '223', '142', '200', '103', '111', '223', 
 '044', '112', '041', '242', '032', '022', '231', '312', '222', '140', '032', '104', '302', 
 '122', '201', '000', '012', '143', '101', '233', '312', '010', '224', '203', '221', '030', 
 '223', '023', '142', '030', '230', '301', '132', '123', '101', '010', '110']

Base 10:
[76,  9, 79, 66, 31, 40, 28, 50, 34, 56, 47, 22, 49, 
 54, 11, 12, 60, 22, 80, 46, 62,  2, 49, 50, 45, 66, 
 30, 35, 55, 24,  7, 12,  9, 25, 52, 40,  8, 73, 82, 
 75,  1, 40, 82, 83, 64, 44, 83, 63,  5, 56, 16, 29, 
 48, 30, 63, 14, 64, 51, 11, 63, 47, 50, 28, 31, 63, 
 24, 32, 21, 72, 17, 12, 66, 82, 62, 45, 17, 29, 77, 
 37, 51,  0,  7, 48, 26, 68, 82,  5, 64, 53, 61, 15, 
 63, 13, 47, 15, 65, 76, 42, 38, 26,  5, 30]
---------------

[EAST 3]
---------------
New reading order:
[2, 2, 1, 0, 1, 4, 3, 0, 4, 0, 0, 0, 1, 0, 0, 3, 0, 2, 2, 2, 0, 2, 3, 1, 2, 2, 2, 2, 3, 2, 1, 4, 4, 1, 4, 4, 2, 1, 1, 
 1, 3, 4, 2, 4, 0, 0, 2, 2, 0, 1, 0, 0, 0, 0, 2, 4, 2, 3, 0, 0, 1, 4, 3, 1, 3, 4, 2, 2, 2, 2, 0, 0, 1, 4, 0, 2, 3, 3, 
 3, 1, 3, 2, 2, 3, 3, 1, 2, 1, 2, 0, 1, 3, 4, 0, 0, 4, 1, 4, 1, 3, 0, 2, 3, 1, 0, 0, 0, 1, 2, 3, 1, 0, 4, 3, 1, 3, 0, 
 2, 3, 0, 0, 1, 1, 0, 2, 2, 2, 1, 1, 3, 0, 0, 0, 0, 1, 1, 1, 3, 2, 1, 2, 1, 2, 0, 2, 0, 0, 0, 4, 1, 0, 2, 0, 0, 2, 0, 
 1, 4, 0, 2, 1, 4, 2, 2, 2, 0, 2, 3, 0, 4, 2, 0, 0, 1, 2, 1, 4, 2, 4, 1, 2, 1, 1, 2, 2, 3, 1, 0, 4, 0, 1, 0, 0, 3, 4, 
 2, 2, 4, 0, 4, 2, 3, 0, 0, 2, 3, 3, 2, 1, 3, 0, 0, 0, 0, 1, 3, 0, 1, 2, 2, 1, 2, 0, 0, 3, 1, 3, 0, 1, 2, 0, 3, 0, 0, 
 0, 0, 1, 2, 4, 0, 2, 4, 1, 0, 2, 0, 2, 3, 2, 0, 4, 3, 0, 4, 3, 0, 3, 1, 2, 2, 4, 1, 3, 1, 3, 1, 2, 3, 0, 1, 1, 4, 2, 
 0, 3, 2, 1, 2, 3, 0, 4, 2, 3, 1, 1, 2, 1, 4, 1, 4, 3, 2, 2, 2, 0, 2, 0, 1, 2, 0, 1, 1, 2, 0, 3, 1, 1, 1, 3, 2, 3, 2, 
 0, 0, 1, 0, 3, 0, 1, 2, 4, 2, 2, 1, 2, 2, 4, 0, 3, 3, 0, 0, 3, 2, 1, 1, 0, 2, 4, 2, 1, 3, 1, 3, 3, 2, 3, 1, 0, 0, 1, 
 1, 4, 0, 0, 0, 4, 3, 0, 4, 0, 3, 3, 2, 2, 4, 1, 1, 1, 2, 1, 4, 1, 3, 0, 2, 3, 4, 0, 0, 3, 3, 0, 1, 0, 1, 2, 0, 1, 4, 
 0, 4, 1, 2, 4, 0, 1, 2, 3, 0, 4, 4, 0, 1, 0, 1, 0, 3, 2, 4, 0]

Tri:
['221', '014', '304', '000', '100', '302', '220', '231', '222', '232', '144', '144', '211', 
 '134', '240', '022', '010', '000', '242', '300', '143', '134', '222', '200', '140', '233', 
 '313', '223', '312', '120', '134', '004', '141', '302', '310', '001', '231', '043', '130', 
 '230', '011', '022', '211', '300', '001', '113', '212', '120', '200', '041', '020', '020', 
 '140', '214', '222', '023', '042', '001', '214', '241', '211', '223', '104', '010', '034', 
 '224', '042', '300', '233', '213', '000', '013', '012', '212', '003', '130', '120', '300', 
 '001', '240', '241', '020', '232', '043', '043', '031', '224', '131', '312', '301', '142', 
 '032', '123', '042', '311', '214', '143', '222', '020', '120', '112', '031', '113', '232', 
 '001', '030', '124', '221', '224', '033', '003', '211', '024', '213', '133', '231', '001', 
 '140', '004', '304', '033', '224', '111', '214', '130', '234', '003', '301', '012', '014', 
 '041', '240', '123', '044', '010', '103', '240']

Base 10:
[61,  9, 79,  0, 25, 77, 60, 66, 62, 67, 49, 49, 56, 
 44, 70, 12,  5,  0, 72, 75, 48, 44, 62, 50, 45, 68, 
 83, 63, 82, 35, 44,  4, 46, 77, 80,  1, 66, 23, 40, 
 65,  6, 12, 56, 75,  1, 33, 57, 35, 50, 21, 10, 10, 
 45, 59, 62, 13, 22,  1, 59, 71, 56, 63, 29,  5, 19,
 64, 22, 75, 68, 58,  0,  8,  7, 57,  3, 40, 35, 75, 
  1, 70, 71, 10, 67, 23, 23, 16, 64, 41, 82, 76, 47, 
 17, 38, 22, 81, 59, 48, 62, 10, 35, 32, 16, 33, 67, 
  1, 15, 39, 61, 64, 18,  3, 56, 14, 58, 43, 66,  1, 
 45,  4, 79, 18, 64, 31, 59, 40, 69,  3, 76,  7,  9, 
 21, 70, 38, 24,  5, 28, 70]
---------------

[WEST 3]
---------------
New reading order:
[1, 1, 1, 0, 1, 4, 3, 0, 4, 0, 4, 4, 0, 2, 3, 1, 0, 1, 0, 3, 3, 2, 3, 2, 1, 2, 0, 1, 1, 3, 2, 4, 0, 0, 3, 2, 0, 2, 3, 
 0, 3, 1, 1, 1, 2, 0, 2, 4, 1, 0, 4, 2, 2, 2, 2, 1, 2, 1, 4, 4, 1, 0, 3, 0, 2, 1, 2, 4, 3, 2, 0, 0, 1, 4, 0, 2, 3, 4, 
 0, 3, 3, 0, 3, 1, 1, 3, 4, 2, 2, 4, 1, 4, 4, 1, 1, 1, 3, 0, 3, 0, 0, 3, 1, 4, 2, 2, 3, 4, 0, 4, 2, 1, 3, 1, 1, 1, 2, 
 1, 2, 0, 0, 3, 4, 1, 1, 1, 3, 0, 2, 0, 3, 2, 1, 3, 4, 2, 1, 1, 2, 0, 2, 1, 4, 1, 0, 1, 2, 0, 0, 2, 3, 1, 4, 1, 3, 4, 
 1, 0, 3, 1, 3, 3, 2, 1, 4, 2, 0, 0, 2, 3, 0, 0, 1, 1, 1, 4, 3, 0, 3, 4, 1, 4, 3, 0, 3, 3, 1, 1, 0, 1, 2, 2, 1, 2, 0, 
 0, 0, 2, 2, 2, 0, 1, 1, 3, 0, 2, 0, 1, 3, 2, 1, 2, 3, 1, 3, 1, 0, 1, 3, 2, 4, 4, 0, 2, 1, 1, 1, 2, 2, 3, 1, 1, 0, 1, 
 1, 2, 0, 1, 2, 0, 1, 2, 3, 1, 3, 0, 0, 1, 1, 0, 2, 4, 0, 1, 4, 1, 3, 3, 0, 2, 1, 0, 2, 3, 0, 0, 2, 2, 2, 0, 0, 4, 4,
 0, 2, 2, 1, 3, 1, 2, 3, 3, 1, 4, 1, 2, 4, 1, 2, 3, 2, 3, 0, 0, 2, 2, 1, 0, 4, 4, 1, 0, 0, 0, 2, 2, 2, 1, 3, 0, 1, 2, 
 1, 2, 0, 2, 2, 4, 0, 2, 2, 2, 3, 4, 2, 0, 3, 0, 3, 3, 1, 2, 0, 2, 4, 4, 0, 4, 0, 2, 0, 0, 2, 4, 4, 1, 1, 4, 2, 0, 4, 
 3, 0, 1, 2, 4, 2, 2, 0, 1, 1, 4, 1, 0, 0, 1, 1, 2, 1, 2, 0, 0]

Tri:
['111', '014', '304', '044', '023', '101', '033', '232', '120', '113', '240', '032', '023', 
 '031', '112', '024', '104', '222', '212', '144', '103', '021', '243', '200', '140', '234', 
 '033', '031', '134', '224', '144', '111', '303', '003', '142', '234', '042', '131', '112', 
 '120', '034', '111', '302', '032', '134', '211', '202', '141', '012', '002', '314', '134', 
 '103', '133', '214', '200', '230', '011', '143', '034', '143', '033', '110', '122', '120', 
 '002', '220', '113', '020', '132', '123', '131', '013', '244', '021', '112', '231', '101', 
 '120', '120', '123', '130', '011', '024', '014', '133', '021', '023', '002', '220', '044', 
 '022', '131', '233', '141', '241', '232', '300', '221', '044', '100', '022', '213', '012', 
 '120', '224', '022', '234', '203', '033', '120', '244', '040', '200', '244', '114', '204', 
 '301', '242', '201', '141', '001', '121', '200']

Base 10:
[31,  9, 79, 24, 13, 26, 18, 67, 35, 33, 70, 17, 13, 
 16, 32, 14, 29, 62, 57, 49, 28, 11, 73, 50, 45, 69, 
 18, 16, 44, 64, 49, 31, 78,  3, 47, 69, 22, 41, 32, 
 35, 19, 31, 77, 17, 44, 56, 52, 46,  7,  2, 84, 44, 
 28, 43, 59, 50, 65,  6, 48, 19, 48, 18, 30, 37, 35,
  2, 60, 33, 10, 42, 38, 41,  8, 74, 11, 32, 66, 26, 
 35, 35, 38, 40,  6, 14,  9, 43, 11, 13,  2, 60, 24, 
 12, 41, 68, 46, 71, 67, 75, 61, 24, 25, 12, 58,  7, 
 35, 64, 12, 69, 53, 18, 35, 74, 20, 50, 74, 34, 54, 
 76, 72, 51, 46,  1, 36, 50]
---------------

[EAST 4]
---------------
New reading order:
[1, 0, 1, 0, 1, 4, 3, 0, 4, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 2, 1, 3, 2, 3, 3, 1, 2, 0, 1, 4, 2, 1, 3, 3, 0, 0, 3, 
 0, 3, 1, 1, 2, 4, 3, 0, 2, 0, 1, 1, 0, 0, 3, 0, 3, 4, 0, 3, 4, 2, 1, 2, 1, 3, 4, 2, 2, 2, 2, 0, 0, 1, 4, 0, 2, 3, 2, 
 1, 0, 1, 0, 0, 4, 2, 2, 3, 2, 1, 0, 0, 3, 4, 3, 0, 0, 1, 4, 4, 2, 1, 4, 2, 2, 4, 0, 2, 2, 2, 0, 0, 3, 0, 0, 0, 2, 2, 
 1, 4, 1, 0, 1, 0, 2, 4, 1, 1, 4, 4, 2, 2, 2, 0, 3, 0, 2, 0, 3, 3, 0, 4, 2, 0, 2, 3, 1, 3, 2, 2, 0, 1, 1, 4, 3, 0, 3, 
 1, 4, 3, 2, 3, 4, 3, 0, 0, 1, 2, 0, 2, 4, 2, 2, 3, 0, 1, 1, 0, 3, 0, 1, 3, 0, 2, 0, 0, 1, 0, 4, 0, 0, 3, 0, 1, 3, 0, 
 2, 2, 3, 3, 0, 3, 2, 2, 2, 2, 1, 4, 2, 1, 4, 1, 0, 3, 1, 4, 4, 2, 0, 3, 1, 4, 3, 1, 4, 3, 1, 0, 4, 2, 3, 3, 2, 1, 0, 
 2, 1, 2, 2, 2, 2, 1, 4, 3, 1, 3, 0, 3, 0, 2, 0, 1, 3, 1, 0, 2, 1, 1, 3, 1, 0, 2, 2, 3, 0, 0, 0, 3, 1, 0, 3, 2, 3, 2, 
 1, 3, 2, 0, 2, 1, 0, 4, 4, 1, 3, 4, 2, 1, 1, 3, 0, 1, 2, 2, 1, 0, 0, 2, 3, 0, 4, 2, 3, 0, 1, 1, 4, 1, 3, 3, 2, 3, 4, 
 1, 2, 2, 0, 2, 4, 2, 3, 0, 1, 0, 1, 3, 1, 1, 2, 3, 2, 2, 1, 3, 0, 3, 4, 3, 0, 4, 3, 0, 3, 2, 3, 0, 0, 1, 0, 2, 2, 0, 
 1, 2, 1, 2, 4, 3]

Tri:
['101', '014', '304', '000', '100', '000', '010', '213', '233', '120', '142', '133', '003', 
 '031', '124', '302', '011', '003', '034', '034', '212', '134', '222', '200', '140', '232', 
 '101', '004', '223', '210', '034', '300', '144', '214', '224', '022', '200', '300', '022', 
 '141', '010', '241', '144', '222', '030', '203', '304', '202', '313', '220', '114', '303', 
 '143', '234', '300', '120', '242', '230', '110', '301', '302', '001', '040', '030', '130', 
 '223', '303', '222', '214', '214', '103', '144', '203', '143', '143', '104', '233', '210', 
 '212', '222', '143', '130', '302', '013', '102', '113', '102', '230', '003', '103', '232', 
 '132', '021', '044', '134', '211', '301', '221', '002', '304', '230', '114', '133', '234', 
 '122', '024', '230', '101', '311', '232', '213', '034', '304', '303', '230', '010', '220', 
 '121', '243']

Base 10:
[26,  9, 79,  0, 25,  0,  5, 58, 68, 35, 47, 43,  3, 
 16, 39, 77,  6,  3, 19, 19, 57, 44, 62, 50, 45, 67, 
 26,  4, 63, 55, 19, 75, 49, 59, 64, 12, 50, 75, 12, 
 46,  5, 71, 49, 62, 15, 53, 79, 52, 83, 60, 34, 78, 
 48, 69, 75, 35, 72, 65, 30, 76, 77,  1, 20, 15, 40, 
 63, 78, 62, 59, 59, 28, 49, 53, 48, 48, 29, 68, 55, 
 57, 62, 48, 40, 77,  8, 27, 33, 27, 65,  3, 28, 67, 
 42, 11, 24, 44, 56, 76, 61,  2, 79, 65, 34, 43, 69, 
 37, 14, 65, 26, 81, 67, 58, 19, 79, 78, 65,  5, 60, 
 36, 73]
---------------

[WEST 4]
---------------
New reading order:
[3, 0, 1, 0, 1, 4, 3, 0, 4, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 2, 1, 3, 2, 3, 3, 1, 2, 0, 1, 4, 0, 0, 4, 0, 0, 0, 2, 
 2, 4, 1, 3, 1, 1, 2, 2, 2, 0, 1, 1, 0, 0, 3, 0, 3, 4, 0, 3, 4, 2, 1, 2, 1, 3, 4, 2, 2, 2, 2, 0, 0, 1, 4, 0, 2, 3, 2, 
 2, 1, 1, 3, 1, 0, 2, 1, 4, 0, 0, 1, 0, 3, 2, 1, 2, 2, 2, 4, 1, 1, 2, 4, 3, 0, 0, 1, 0, 0, 1, 3, 1, 2, 2, 3, 3, 1, 3, 
 0, 4, 1, 1, 2, 4, 2, 3, 3, 2, 3, 0, 0, 0, 3, 0, 2, 4, 3, 1, 4, 0, 3, 4, 1, 0, 3, 2, 3, 1, 0, 3, 2, 1, 2, 2, 0, 3, 0, 
 0, 4, 0, 2, 1, 0, 2, 4, 0, 1, 0, 3, 2, 0, 2, 2, 1, 0, 2, 4, 3, 0, 2, 1, 0, 1, 2, 1, 0, 3, 0, 1, 2, 0, 3, 3, 2, 3, 2, 
 1, 4, 1, 1, 3, 4, 1, 2, 0, 2, 2, 1, 1, 1, 3, 0, 4, 4, 2, 4, 1, 2, 0, 1, 2, 1, 4, 2, 3, 1, 3, 0, 1, 1, 1, 2, 2, 0, 4, 
 2, 0, 4, 2, 3, 3, 2, 4, 1, 2, 0, 3, 3, 0, 2, 0, 2, 3, 3, 0, 1, 0, 4, 1, 2, 0, 4, 2, 4, 1, 0, 1, 2, 2, 3, 2, 1, 0, 1, 
 0, 4, 4, 1, 2, 2, 0, 3, 0, 0, 4, 4, 2, 3, 1, 0, 4, 2, 0, 1, 4, 2, 2, 1, 2, 3, 2, 1, 2, 4, 1, 1, 3, 0, 4, 1, 1, 1, 3, 
 2, 2, 4, 3, 1, 4, 1, 1, 4, 0, 4, 2, 1, 2, 1, 1, 1, 4, 1, 4, 0, 1, 3, 0, 1, 1, 0, 0, 4, 1, 2, 0, 1, 0, 0, 0, 1, 3, 0, 
 0, 0, 0, 1, 3, 2, 0, 2, 0]

Tri:
['301', '014', '304', '000', '100', '000', '010', '213', '233', '120', '140', '040', '002', 
 '241', '311', '222', '011', '003', '034', '034', '212', '134', '222', '200', '140', '232', 
 '211', '310', '214', '001', '032', '122', '241', '124', '300', '100', '131', '223', '313', 
 '041', '124', '233', '230', '003', '024', '314', '034', '103', '231', '032', '122', '030', 
 '040', '210', '240', '103', '202', '210', '243', '021', '012', '103', '012', '033', '232', 
 '141', '134', '120', '221', '113', '044', '241', '201', '214', '231', '301', '112', '204', 
 '204', '233', '241', '203', '302', '023', '301', '041', '204', '241', '012', '232', '101', 
 '044', '122', '030', '044', '231', '042', '014', '221', '232', '124', '113', '041', '113', 
 '224', '314', '114', '042', '121', '114', '140', '130', '110', '041', '201', '000', '130', 
 '000', '132', '020']

Base 10:
[76,  9, 79,  0, 25,  0,  5, 58, 68, 35, 45, 20,  2, 
 71, 81, 62,  6,  3, 19, 19, 57, 44, 62, 50, 45, 67, 
 56, 80, 59,  1, 17, 37, 71, 39, 75, 25, 41, 63, 83, 
 21, 39, 68, 65,  3, 14, 84, 19, 28, 66, 17, 37, 15, 
 20, 55, 70, 28, 52, 55, 73, 11,  7, 28,  7, 18, 67, 
 46, 44, 35, 61, 33, 24, 71, 51, 59, 66, 76, 32, 54, 
 54, 68, 71, 53, 77, 13, 76, 21, 54, 71,  7, 67, 26, 
 24, 37, 15, 24, 66, 22,  9, 61, 67, 39, 33, 21, 33, 
 64, 84, 34, 22, 36, 34, 45, 40, 30, 21, 51,  0, 40, 
  0, 42, 10]
---------------

[EAST 5]
---------------
New reading order:
[1, 1, 1, 0, 1, 4, 3, 0, 4, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 2, 1, 3, 2, 3, 3, 1, 2, 0, 1, 4, 3, 0, 4, 4, 1, 3, 3, 
 0, 3, 4, 2, 1, 1, 1, 1, 2, 0, 1, 1, 0, 0, 3, 0, 3, 4, 0, 3, 4, 2, 1, 2, 1, 3, 4, 2, 2, 2, 2, 0, 0, 1, 4, 0, 2, 3, 3, 
 1, 0, 1, 2, 1, 4, 2, 2, 3, 3, 0, 2, 0, 2, 4, 0, 1, 4, 1, 4, 4, 2, 1, 2, 2, 2, 2, 2, 3, 0, 2, 1, 2, 2, 1, 3, 2, 3, 3, 
 2, 0, 2, 1, 4, 3, 0, 4, 2, 0, 2, 4, 2, 4, 2, 2, 0, 0, 2, 0, 3, 1, 4, 0, 2, 0, 2, 1, 0, 4, 2, 2, 0, 1, 1, 4, 3, 0, 3, 
 0, 1, 4, 1, 1, 0, 1, 1, 4, 1, 0, 3, 1, 1, 1, 0, 1, 0, 2, 4, 0, 1, 1, 0, 2, 0, 4, 0, 1, 0, 0, 1, 3, 1, 0, 0, 1, 3, 0, 
 3, 1, 2, 1, 4, 0, 0, 4, 0, 2, 2, 1, 0, 1, 4, 3, 0, 4, 2, 1, 1, 1, 1, 2, 1, 4, 4, 0, 1, 1, 0, 3, 1, 1, 1, 2, 1, 1, 2, 
 1, 0, 2, 0, 4, 1, 0, 4, 1, 2, 2, 1, 1, 3, 4, 1, 3, 0, 1, 3, 3, 0, 1, 3, 2, 4, 3, 0, 1, 1, 0, 4, 2, 0, 1, 0, 2, 2, 1, 
 2, 0, 1, 1, 3, 0, 2, 4, 1, 1, 1, 1, 2, 4, 0, 1, 1, 3, 2, 4, 4, 0, 2, 1, 0, 1, 0, 0, 4, 2, 2, 0, 0, 3, 0, 2, 0, 2, 0, 
 1, 3, 1, 2, 2, 4, 2, 2, 0, 2, 2, 2, 0, 4, 1, 1, 3, 4, 1, 3, 3, 1, 0, 1, 2, 4, 4, 2, 3, 2]      

Tri:
['111', '014', '304', '000', '100', '000', '010', '213', '233', '120', '143', '044', '133', 
 '034', '211', '112', '011', '003', '034', '034', '212', '134', '222', '200', '140', '233', 
 '101', '214', '223', '302', '024', '014', '144', '212', '222', '230', '212', '213', '233', 
 '202', '143', '042', '024', '242', '200', '203', '140', '202', '104', '220', '114', '303', 
 '014', '110', '114', '103', '111', '010', '240', '110', '204', '010', '013', '100', '130', 
 '312', '140', '040', '221', '014', '304', '211', '112', '144', '011', '031', '112', '112', 
 '102', '041', '041', '221', '134', '130', '133', '013', '243', '011', '042', '010', '221', 
 '201', '130', '241', '111', '240', '113', '244', '021', '010', '042', '200', '302', '020', 
 '131', '224', '220', '222', '041', '134', '133', '101', '244', '232']

Base 10:
[31,  9, 79,  0, 25,  0,  5, 58, 68, 35, 48, 24, 43, 
 19, 56, 32,  6,  3, 19, 19, 57, 44, 62, 50, 45, 68, 
 26, 59, 63, 77, 14,  9, 49, 57, 62, 65, 57, 58, 68, 
 52, 48, 22, 14, 72, 50, 53, 45, 52, 29, 60, 34, 78, 
  9, 30, 34, 28, 31,  5, 70, 30, 54,  5,  8, 25, 40, 
 82, 45, 20, 61,  9, 79, 56, 32, 49,  6, 16, 32, 32, 
 27, 21, 21, 61, 44, 40, 43,  8, 73,  6, 22,  5, 61, 
 51, 40, 71, 31, 70, 33, 74, 11,  5, 22, 50, 77, 10, 
 41, 64, 60, 62, 21, 44, 43, 26, 74, 67]
---------------

[ALL]
---------------
Base 10:
[51,  8, 63, 79, 21, 40, 67, 34, 83, 18,  4, 14,  0, 
 81, 48, 27, 75,  6, 12, 61, 72, 64, 25, 12, 45, 65, 
 80, 61, 24,  0, 50, 29, 20, 49, 47, 18, 12, 19, 71, 
 32, 49, 48, 49, 43, 42, 71, 11, 66, 40, 16, 83, 42, 
  9,  3, 57, 34, 40, 21, 30, 25, 71, 71,  4, 16,  1, 
 54, 74, 74, 59, 11, 20,  5, 26, 61, 48, 69, 43, 20, 
 43, 82, 53, 76, 16, 41, 32, 32, 28, 63, 48, 44, 13, 
 58, 10, 34, 15, 84, 64, 70, 41, 81,  8, 63, 79, 21, 
 40, 67, 34, 83, 18,  4, 14,  4, 26, 48, 27, 75,  6, 
 12, 61, 72, 64, 25, 12, 45, 65, 10, 51, 24,  0, 29, 
 24, 20, 49, 47, 18, 12, 19, 41, 29, 49, 48, 49, 43, 
 42, 71, 10, 51, 25, 16, 82, 31, 57, 63, 78, 74,  0, 
 73, 66, 30, 61, 66, 16, 12, 23, 66, 18, 37, 48, 84, 
 28,  7, 23, 31, 62, 29, 44, 79, 14, 47, 59, 62, 15, 
 72,  1, 67, 39, 13, 67,  9, 18, 34, 63, 40, 42, 70, 
 12, 63, 10, 82, 32, 66,  8, 36,  8, 63, 79, 21, 40, 
 67, 34, 83, 18,  4, 14,  4, 66, 48, 27, 75,  6, 12, 
 61, 72, 64, 25, 12, 45, 66, 77,  8, 65, 24, 55, 48, 
  1, 59, 45, 81, 14, 29, 63, 64, 49, 63,  5, 42, 16, 
 18, 79, 42, 62, 81, 49, 51,  9, 33, 15, 49, 27, 10, 
 81, 34, 71, 19, 67, 42, 32, 20, 37, 76,  0, 20, 54, 
 61, 60, 76, 20, 11, 11, 46,  1, 42, 55, 22, 66, 23, 
 72,  8, 28,  5, 50, 75, 61, 64, 27, 49,  8, 76,  0, 
 42, 18, 40, 58, 22, 71, 10, 19, 51, 23, 26, 25, 50, 
 39, 33, 63, 46, 10, 60, 54, 41, 76,  9, 79, 66, 31, 
 40, 28, 50, 34, 56, 47, 22, 49, 54, 11, 12, 60, 22, 
 80, 46, 62,  2, 49, 50, 45, 66, 30, 35, 55, 24,  7, 
 12,  9, 25, 52, 40,  8, 73, 82, 75,  1, 40, 82, 83, 
 64, 44, 83, 63,  5, 56, 16, 29, 48, 30, 63, 14, 64, 
 51, 11, 63, 47, 50, 28, 31, 63, 24, 32, 21, 72, 17, 
 12, 66, 82, 62, 45, 17, 29, 77, 37, 51,  0,  7, 48, 
 26, 68, 82,  5, 64, 53, 61, 15, 63, 13, 47, 15, 65, 
 76, 42, 38, 26,  5, 30, 61,  9, 79,  0, 25, 77, 60, 
 66, 62, 67, 49, 49, 56, 44, 70, 12,  5,  0, 72, 75, 
 48, 44, 62, 50, 45, 68, 83, 63, 82, 35, 44,  4, 46, 
 77, 80,  1, 66, 23, 40, 65,  6, 12, 56, 75,  1, 33, 
 57, 35, 50, 21, 10, 10, 45, 59, 62, 13, 22,  1, 59, 
 71, 56, 63, 29,  5, 19, 64, 22, 75, 68, 58,  0,  8, 
  7, 57,  3, 40, 35, 75,  1, 70, 71, 10, 67, 23, 23, 
 16, 64, 41, 82, 76, 47, 17, 38, 22, 81, 59, 48, 62, 
 10, 35, 32, 16, 33, 67,  1, 15, 39, 61, 64, 18,  3, 
 56, 14, 58, 43, 66,  1, 45,  4, 79, 18, 64, 31, 59, 
 40, 69,  3, 76,  7,  9, 21, 70, 38, 24,  5, 28, 70, 
 31,  9, 79, 24, 13, 26, 18, 67, 35, 33, 70, 17, 13, 
 16, 32, 14, 29, 62, 57, 49, 28, 11, 73, 50, 45, 69, 
 18, 16, 44, 64, 49, 31, 78,  3, 47, 69, 22, 41, 32, 
 35, 19, 31, 77, 17, 44, 56, 52, 46,  7,  2, 84, 44, 
 28, 43, 59, 50, 65,  6, 48, 19, 48, 18, 30, 37, 35, 
  2, 60, 33, 10, 42, 38, 41,  8, 74, 11, 32, 66, 26, 
 35, 35, 38, 40,  6, 14,  9, 43, 11, 13,  2, 60, 24, 
 12, 41, 68, 46, 71, 67, 75, 61, 24, 25, 12, 58,  7, 
 35, 64, 12, 69, 53, 18, 35, 74, 20, 50, 74, 34, 54, 
 76, 72, 51, 46,  1, 36, 50, 26,  9, 79,  0, 25,  0, 
  5, 58, 68, 35, 47, 43,  3, 16, 39, 77,  6,  3, 19, 
 19, 57, 44, 62, 50, 45, 67, 26,  4, 63, 55, 19, 75, 
 49, 59, 64, 12, 50, 75, 12, 46,  5, 71, 49, 62, 15, 
 53, 79, 52, 83, 60, 34, 78, 48, 69, 75, 35, 72, 65, 
 30, 76, 77,  1, 20, 15, 40, 63, 78, 62, 59, 59, 28, 
 49, 53, 48, 48, 29, 68, 55, 57, 62, 48, 40, 77,  8, 
 27, 33, 27, 65,  3, 28, 67, 42, 11, 24, 44, 56, 76, 
 61,  2, 79, 65, 34, 43, 69, 37, 14, 65, 26, 81, 67, 
 58, 19, 79, 78, 65,  5, 60, 36, 73, 76,  9, 79,  0, 
 25,  0,  5, 58, 68, 35, 45, 20,  2, 71, 81, 62,  6, 
  3, 19, 19, 57, 44, 62, 50, 45, 67, 56, 80, 59,  1, 
 17, 37, 71, 39, 75, 25, 41, 63, 83, 21, 39, 68, 65, 
  3, 14, 84, 19, 28, 66, 17, 37, 15, 20, 55, 70, 28, 
 52, 55, 73, 11,  7, 28,  7, 18, 67, 46, 44, 35, 61, 
 33, 24, 71, 51, 59, 66, 76, 32, 54, 54, 68, 71, 53, 
 77, 13, 76, 21, 54, 71,  7, 67, 26, 24, 37, 15, 24, 
 66, 22,  9, 61, 67, 39, 33, 21, 33, 64, 84, 34, 22, 
 36, 34, 45, 40, 30, 21, 51,  0, 40,  0, 42, 10, 31, 
  9, 79,  0, 25,  0,  5, 58, 68, 35, 48, 24, 43, 19, 
 56, 32,  6,  3, 19, 19, 57, 44, 62, 50, 45, 68, 26, 
 59, 63, 77, 14,  9, 49, 57, 62, 65, 57, 58, 68, 52, 
 48, 22, 14, 72, 50, 53, 45, 52, 29, 60, 34, 78,  9, 
 30, 34, 28, 31,  5, 70, 30, 54,  5,  8, 25, 40, 82, 
 45, 20, 61,  9, 79, 56, 32, 49,  6, 16, 32, 32, 27, 
 21, 21, 61, 44, 40, 43,  8, 73,  6, 22,  5, 61, 51, 
 40, 71, 31, 70, 33, 74, 11,  5, 22, 50, 77, 10, 41, 
 64, 60, 62, 21, 44, 43, 26, 74, 67]
 ---------------
```

## Test2 - Different Reading Order

The accepted trigram values but all right-side up triangles are read first, then the upside down ones starting from the end.

You can view a more detailed analysis here:
link

Here is the output of the python script:

```
EAST 1:
['231', '143', '023', '104', '221', '240', '222', '024', '013', '303', '104', '144', '310', 
 '130', '311', '034', '130', '230', '024', '240', '134', '132', '143', '142', '144', '111', 
 '044', '133', '232', '144', '220', '101', '010', '040', '021', '211', '244', '241', '201', 
 '133', '242', '223', '311', '031', '111', '022', '212', '023', '133', '143', '224', '103', 
 '113', '110', '134', '030', '304', '204', '310', '131', '004', '034', '004', '244', '241', 
 '100', '110', '041', '131', '113', '214', '003', '010', '242', '034', '023', '034', '143', 
 '142', '041', '101', '201', '000', '041', '223', '312', '001', '023', '002', '030', '311', 
 '112', '231', '132', '044', '300', '222', '010', '200']

WEST 1:
['231', '143', '023', '104', '221', '240', '222', '024', '013', '303', '104', '144', '104', 
 '110', '311', '034', '100', '204', '024', '240', '134', '132', '143', '142', '144', '101', 
 '302', '133', '103', '224', '110', '043', '011', '100', '311', '141', '121', '032', '233', 
 '014', '232', '114', '312', '020', '222', '021', '242', '134', '133', '222', '114', '033', 
 '014', '233', '020', '122', '230', '002', '243', '030', '222', '212', '141', '023', '041', 
 '023', '032', '233', '224', '113', '232', '243', '001', '242', '304', '224', '214', '134', 
 '034', '023', '034', '143', '142', '041', '040', '101', '000', '041', '202', '021', '001',
 '023', '002', '030', '311', '112', '231', '132', '044', '300', '222', '010', '310']

EAST 2:
['231', '143', '023', '104', '221', '240', '222', '024', '013', '303', '104', '144', '234', 
 '202', '143', '310', '224', '130', '303', '031', '034', '130', '011', '224', '144', '223', 
 '144', '023', '020', '044', '302', '220', '221', '204', '041', '004', '302', '122', '042', 
 '021', '242', '040', '212', '131', '033', '132', '003', '303', '010', '140', '100', '221', 
 '134', '201', '223', '021', '140', '220', '114', '123', '203', '101', '100', '040', '204', 
 '031', '224', '302', '204', '013', '101', '010', '242', '043', '230', '043', '212', '131', 
 '000', '110', '132', '231', '030', '240', '114', '311', '020', '101', '140', '031', '111', 
 '011', '224', '104', '023', '310', '142', '211', '003', '144', '212', '042', '231', '014', 
 '301', '001', '023', '002', '030', '311', '112', '231', '132', '044', '300', '222', '010', 
 '121']

WEST 2:
['231', '144', '204', '141', '001', '220', '143', '310', '044', '221', '022', '022', '204', 
 '100', '030', '210', '014', '222', '312', '134', '220', '312', '310', '133', '003', '302', 
 '303', '100', '033', '144', '224', '311', '231', '023', '032', '240', '043', '111', '043', 
 '112', '011', '100', '122', '133', '301', '233', '032', '140', '024', '223', '031', '220', 
 '203', '223', '012', '310', '230', '101', '142', '013', '001', '200', '120', '224', '112', 
 '101', '202', '142', '222', '021', '202', '222', '020', '222', '114', '142', '310', '241', 
 '010', '132', '203', '104', '014', '023', '013', '040', '211', '121', '114', '144', '041', 
 '142', '210', '112', '200', '101', '132', '112', '234', '300', '010', '301']

EAST 3:
['231', '144', '204', '220', '130', '142', '300', '241', '002', '012', '024', '244', '131', 
 '023', '023', '042', '200', '124', '214', '111', '002', '300', '211', '021', '013', '230', 
 '300', '124', '132', '003', '212', '011', '014', '001', '211', '233', '304', '040', '224', 
 '231', '110', '031', '110', '122', '023', '223', '141', '214', '311', '042', '121', '032', 
 '011', '010', '304', '001', '234', '133', '213', '111', '224', '033', '303', '001', '141', 
 '241', '100', '013', '044', '120', '243', '040', '000', '234', '134', '213', '024', '211', 
 '004', '030', '224', '223', '121', '032', '004', '142', '303', '312', '131', '224', '033', 
 '042', '040', '230', '022', '241', '243', '002', '034', '012', '100', '223', '213', '240', 
 '213', '002', '042', '023', '220', '210', '140', '130', '041', '232', '001', '310', '301', 
 '143', '002', '130', '120', '311', '220', '310', '214', '140', '142', '230', '220', '232', 
 '220', '303', '104', '002', '300', '010', '223']

WEST 3:
['231', '144', '204', '244', '023', '101', '143', '212', '220', '103', '020', '112', '033', 
 '133', '311', '004', '014', '144', '201', '213', '133', '032', '304', '112', '031', '122', 
 '103', '233', '114', '020', '240', '011', '133', '124', '133', '023', '110', '222', '000', 
 '010', '210', '023', '100', '041', '224', '304', '233', '241', '143', '232', '130', '024', 
 '200', '124', '002', '144', '203', '243', '300', '204', '110', '240', '204', '044', '244', 
 '121', '032', '201', '231', '021', '221', '120', '042', '221', '003', '021', '021', '132', 
 '010', '021', '014', '130', '122', '123', '122', '122', '120', '113', '030', '142', '033', 
 '141', '013', '234', '201', '212', '131', '101', '110', '134', '041', '232', '142', '004', 
 '301', '112', '141', '222', '132', '034', '034', '021', '032', '244', '114', '122', '232', 
 '034', '103', '021', '043', '300', '010', '114']

EAST 4:
['231', '144', '204', '220', '130', '210', '030', '033', '003', '010', '302', '123', '033', 
 '301', '114', '223', '310', '204', '300', '204', '034', '224', '142', '240', '010', '142', 
 '213', '234', '100', '140', '142', '200', '140', '101', '212', '211', '220', '300', '220', 
 '232', '132', '113', '230', '302', '003', '222', '303', '212', '130', '043', '023', '132', 
 '242', '124', '220', '011', '231', '302', '303', '034', '214', '233', '310', '100', '230', 
 '021', '123', '232', '101', '004', '234', '101', '111', '101', '012', '304', '130', '144', 
 '223', '214', '133', '033', '042', '004', '304', '303', '114', '233', '243', '123', '304', 
 '233', '140', '021', '300', '201', '024', '222', '210', '143', '304', '032', '213', '220', 
 '004', '103', '001', '134', '142', '121', '233', '214', '014', '002', '104', '002', '300', 
 '010', '102']

WEST 4:
['231', '144', '204', '220', '130', '210', '030', '033', '003', '010', '220', '310', '242', 
 '031', '120', '034', '231', '102', '032', '311', '024', '000', '230', '231', '123', '043', 
 '200', '110', '300', '233', '212', '200', '243', '041', '112', '223', '122', '133', '142', 
 '114', '043', '111', '123', '232', '223', '011', '041', '234', '041', '032', '122', '041', 
 '024', '134', '004', '132', '001', '204', '040', '110', '130', '141', '111', '120', '040', 
 '110', '312', '220', '104', '232', '010', '244', '201', '042', '304', '021', '302', '204', 
 '243', '231', '203', '231', '034', '010', '101', '013', '024', '241', '211', '204', '101', 
 '241', '212', '044', '311', '224', '133', '100', '303', '124', '244', '124', '033', '001', 
 '212', '312', '210', '001', '041', '142', '121', '233', '214', '014', '002', '104', '002', 
 '300', '010', '302']

EAST 5:
['231', '144', '204', '220', '130', '210', '030', '033', '003', '010', '113', '214', '033', 
 '301', '114', '223', '102', '204', '144', '204', '202', '242', '020', '042', '143', '203', 
 '114', '110', '034', '013', '141', '110', '210', '300', '014', '220', '043', '140', '310', 
 '022', '301', '201', '041', '014', '020', '243', '113', '243', '111', '242', '130', '201', 
 '231', '244', '100', '132', '131', '044', '223', '221', '224', '132', '221', '010', '041', 
 '011', '240', '013', '134', '131', '130', '222', '040', '042', '100', '132', '100', '010', 
 '011', '204', '114', '241', '012', '114', '101', '111', '112', '012', '232', '213', '212', 
 '234', '222', '210', '143', '010', '022', '304', '220', '214', '103', '134', '041', '142', 
 '121', '233', '214', '014', '002', '104', '002', '300', '010', '113']
```