spawn = require('child_process').spawn

task 'doc', 'Make documents', ->
  command = './bin/crojsdoc'
  args = ['-q','-f','--title','CroJSDoc','lib','examples','guides']
  spawn command, args, stdio: 'inherit'