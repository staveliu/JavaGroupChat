# Java Group Chat System
## **Library**
  Gson 2.8.5 for json resolve
  Java Socket
## **User Database**
  Via server.data.json
## **Package structure**
  -- server (Server)
  
    -- Server.java -- Server Main Class
    
    -- ServerThread.java -- Handle the user command and message forwarding
    
    -- User.java -- User datastructure and control json.
    
  -- graphClient (Client with UI)
  
    -- Listener.java -- Listen the action of frame
    
    -- ChatFrame.java -- Main Chat Frame
    
    -- ClientWindow.java -- Login frame
    
    -- ClientWindowMain.java -- Client Main Class. Handle the action of login
    
    -- ReadThread.java -- Read thread of Client
    
    -- WriteThread.java -- Write thread of Client
    
  -- commandLineClient (Client without UI, CommandLine Interface)
  
    -- Client.java -- Main Client Class. Handle the action
    
    -- ReadThread.java -- Read thread of Client
    
    -- WriteThread.java -- Write thread of Client
    
    
 
