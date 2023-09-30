# Repo of Action
This repo is a collection of simple action files used to learn Github Actions.

## push_a_change.yml
This github action:..
  1. pulls the repo
  2. echo an 'x' then >> it to the end of xs.txt file
  3. git adds the change
  4. commits  the change with a (kind of extraneous) timestamp for when the change was made
  5. pushes the change

## log_as_csv.yml
This github action:..
  1. pulls the repo
  2. runs formated git log then > it to log.csv file
  3. runs sed to filter out any changes made by this action
  4. git adds the change
  5. git commits the change with "automatic log update" message
  6. pushes the change
