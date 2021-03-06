
Server-side validation
-------

**Description:**

Whenever the application is processing high value business logic parameters these values 
should always be processed out of reach of the users and validated against expected
values on the server.


**Solution:**

Verify the application does not allow high value business logic parameters to be 
tampered with. The users should not be able to have control over this value, recommended 
is to process this data server-side and validate the data to see if it returns expected 
values. If not these failures should be logged.

Also important to always verify that the same access control rules implied by the presentation layer 
are enforced on the serverside.

Recommended knowledge base items:

- Input validation 
- Input rejection
- Single input validation class
- Character encoding
- Client side input validation
