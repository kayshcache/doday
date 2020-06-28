# ToDoday
ToDoday app "Do today what you could do tomorrow" list all desired tasks and daily routine items and have them shuffled on a two day cycle until marked done. If it doesn't get done tomorrow you lose your streak. Reselect your tasks from the failed list, excluding anything that is impossible to get done by tomorrow. (but that list gets kept in the background and may randomly ask to be added back on)
## features: 
- add routine/task
- mark done
- mark can not be done
- NO remove (part of the game) everything you add you have to do today or tomorrow or you lose
- losing game: state resets but todo list re-instantiates with option then to remove what CAN NOT be done by tomorrow.
- if not today it moves to tomorrow with priority
## objects
2 classes of todo objects: routines, tasks
both on a today or tomorrow schedule --- therefore click not today and it becomes tomorrows warning todo - if failure to do tomorrow GAME OVER.
Gamified with "doing streak" score + "done-a-lot" points board
Post-mvp ideas: flutter app / notifications / gnome extension
