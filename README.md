#  复旦大学体育场馆自动预约 FDU Sports Auto Reserve

DISCLAIMER: Use at your own risk. The author is, to the extent permitted by law, not responsible for whatever happens during your use of this script, or caused by the script itself. This script comes with ABSOLUTELY no warranty.

## Usage
- Replace strings in `main.py` with the appropriate values.
- Run the script

You may set the log level in `logs.py`

### password update
- In case your id and pw is revealed.
- Use `os.getenv()` to obtain environment dict (keys "STD_ID" and "STD_PW")
- Remember to add these two items to the repo secrets.


## Known issues
- The script may on rare occasions fail to login. But this happens on browser too so there's nothing I can do about it. Wait and try again later.
