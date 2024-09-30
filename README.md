# 4-2Assignment-AnatomyofaREADME
from crud_module import create

# Define the new data entry
new_entry = {
'id': 2,
'name': 'Vinita Ravivarma',
'email': 'vinitavarma6@gmail.com
}

# Call the create function
create(new_entry)

-------------------------------------
from crud_module import read

# Call the read function
entries = read()

# Display all entries
for entry in entries:
    print(entry)
