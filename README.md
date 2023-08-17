# Append to a file, then push
This is a github action that:
  1. pulls the repo
  2. echo an 'x' then >> it to the end of xs.txt file
  3. git adds the change
  4. commits  the change with a timestamp for when the change was made
  5. pushes the change
