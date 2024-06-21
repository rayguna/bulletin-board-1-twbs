# Bootstrapping Bulletin Board 1

Target: https://bulletin-board-bootstrap.matchthetarget.com/

Lesson: https://learn.firstdraft.com/lessons/138-bootstrap-bulletin-board-1

Resources: 
- bootstrap: https://learn.firstdraft.com/lessons/139-intro-to-bootstrap
- alert: https://getbootstrap.com/docs/5.3/components/alerts/
- navbar: https://getbootstrap.com/docs/5.3/components/navbar/#nav

<hr>: 
Notes:

1. Run the server with: bin/server
2. Populate tables with rake sample_data
3. Add css script and its dependencies in the <head> tag of application.html.erb.
4. Add css navbar to application.html.erb. Include the modal script to pop out a form when the "Add a new board" button is clicked.
5. Make sure to specify the value for the hidden path_id within the css <!--modal--> section:

```
<input type="hidden" id="board_id_box" name="query_board_id" value=<%=params.fetch("path_id")%>>
```
