# Muse2 EEG Dataset Documentation

## Overview
This repository contains EEG data collected from eight volunteers engaged in six different activities, using the Muse2 headband equipped with a four-channel EEG sensor setup. The dataset is intended for research into human cognitive and physiological responses under various conditions.

### Participant Consent
All data included in this repository were collected from volunteers at our school laboratory who provided informed consent for the use of their EEG data in research and for public dissemination. Each participant was fully informed about the nature of the study, the use of the data, and their rights, including the right to withdraw from the study at any time without any consequences.

### Pending Ethical Approval
The study is currently under review for formal ethical approval by the Guangdong University of Technology Committee. This process is to ensure that all research activities adhere to the highest ethical standards set forth by Guangdong University of Technology. The final approval is pending, and any necessary modifications will be made to this dataset and its documentation in accordance with the committee's feedback and requirements.

## Data Link
https://www.dropbox.com/scl/fi/kb9xsyov8xdyoiwz1v0zn/Muse2-dataset.zip?rlkey=q0prm5fykrha8234mmqsfcq6z&st=75yz5eve&dl=0

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
