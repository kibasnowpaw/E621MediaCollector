
# E621MediaCollector

E621MediaCollector is a Python script for efficiently downloading media from E621 based on user-defined tags. It provides a convenient way to collect and organize media from E621, a popular online repository for furry and anthropomorphic artwork.
Features
 1. Fetches posts from E621 based on specified tags
 2. Downloads media files concurrently, utilizing multiple threads
 3. Generates .nfo files for each downloaded file, containing metadata information
 4. Supports rate limiting to avoid exceeding API restrictions
 5. Automatically creates folders based on tags for easy organization

# Requirements

1. Python 3.6 or above
2. Requests library (pip install requests)
3. tqdm library (pip install tqdm)

# Usage

1. Configure the script by providing your E621 username and API key in the config.json file.
2. Add the desired tags to the tags.txt file, with each tag on a separate line.
3. Run the script using python E621MediaCollector.py.
4. The script will search for posts matching the specified tags, download the media files, and generate .nfo files in the appropriate folders.

Note: Ensure that you comply with E621's terms of service and usage guidelines when using this script.
License

This script is developed independently and is not affiliated with or endorsed by E621. Use it responsibly and at your own risk.
