# Muse2 EEG Dataset Documentation

## Overview
This repository contains EEG data collected from eight volunteers engaged in six different activities, using the Muse2 headband equipped with a four-channel EEG sensor setup. The dataset is intended for research into human cognitive and physiological responses under various conditions.

## Data Link
https://www.dropbox.com/scl/fi/1vkaq5jjl3m8lx1sxl1fc/Muse2-dataset.zip?rlkey=m9d5muvk4r5yke9uomybq6zsn&st=p8956boi&dl=0

## Data Collection Equipment
- **Device:** Muse2 Headband
- **Channels:**
  - AF7 and AF8 (located at the left and right forehead, respectively)
  - TP9 and TP10 (located behind the left and right ears, respectively)
- **Reference:** One reference EEG channel included
- **Sample Rate:** 256 Hz
- **Resolution:** 12 bits per sample
- **Transmission:** Bluetooth 4.2 for efficient wireless connectivity
- **Power:** Rechargeable Lithium-ion battery with up to 5 hours of continuous usage or 10-15 days with 20-minute daily usage
- **Electrodes:** Conductive gold, strategically placed for optimal signal capture

## Dataset Structure
- **Volunteers:** Data are organized into folders named `volunteer_X` for each of the eight participants.
- **Activities:** Each folder contains CSV files for different activities:
  - `eat_[timestamp].csv` - Eating
  - `game_[timestamp].csv` - Playing online games
  - `read_[timestamp].csv` - Reading
  - `rest_[timestamp].csv` - Resting
  - `toy_[timestamp].csv` - Playing with toys
  - `tv_[timestamp].csv` - Watching TV
- **Data Files:** Each CSV file contains columns for timestamp and raw EEG data from the channels (RAW_TP9, RAW_AF7, RAW_AF8, RAW_TP10).

## Data Format
Each CSV file starts with a header row indicating the timestamp and EEG channels, followed by rows of data recorded during the respective activity.

## Usage Guidelines
This dataset is available for academic and research purposes. Users are encouraged to cite this dataset in any publications resulting from the use of this data.

## How to Download and Cite
- **Download:** Clone this repository or download the files directly from the GitHub page.
- **Citation:** If you use this dataset, please cite it as follows:
Lingyue Hu, Bingo Wing-Kuen Ling, Kailong Zhao, Yiting Wei, "Joint Quaternion Discrete Fourier Transform and Multi-Channel Discrete Fourier Transform Based Activity Recognition via Electroencephalogram," 
