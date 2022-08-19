This is fork from https://github.com/twintproject/twint . It is good tool to parse twitter without getting tokens. There is some issues in original repo with libraries, so I've fixed them for quick use from Collab.

#### HOW TO INSTALL

git clone --depth=2 https://github.com/DmitryVerhov/twint_fixed.git
pip install -r twint_fixed/twint/requirements.txt
pip install twint_fixed/twint

#### Jupiter notebooks

For async to work:

!pip install nest_asyncio
import nest_asyncio
nest_asyncio.apply()
