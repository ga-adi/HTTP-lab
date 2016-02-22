#Will & Claire - Youtube App HTTP Lab

### Main screen to Selected video screen

- Method : GET
- Requested data : Video data(title, uploader, date, views...), ads, comments, recommended videos


### Selected video screen to Channel screen

- Method : GET
- Requested data : Channel backdrop/photo, channel description, playlists, uploads


### Selected video screen to 'Add to your playlist' dialog

- Method : POST
- Requested data : User playlist, selected list, selected video


### Selected video screen to Report dialog

- Method : GET
- Requested data : Report options


### Report dialog to Report button 

- Method : POST
- Requested data : Selected option, reported video



---

#BONUS

##INBOX app

### Main screen to Email content screen 

- Method: GET
- Requested data : Email data


### Email content screen to Forward screen 

- Method : POST 
- Requested data : User info, Email content, previous email content, date, recipient

