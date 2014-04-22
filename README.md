php-rsvp
========

A PHP/MySQL framework for creating websites for accepting RSVPs to weddings and other events.

Guests can RSVP by requesting `rsvp.php?k=[key]` where `[key]` is either randomly generated or chosen randomly from a list of supplied options.

Implemented Features:
- Parties with multiple guests
- Meals, selected during RSVP process
- Emails collected for sending updates parties
- Display of aggregate data (guests invited, total accepted, total per meal type)
- Random generation of URL keys
- Ability to supply preferred URL keys
- Generation of URLs to distribute to potential guests

Planned Features:
- QR codes generated with RSVP URL
- Google Calendar invitations sent on RSVP
- Ability to delete guests, parties, and meals
- Ability to edit guests, parties, and meals (can only add currently)
