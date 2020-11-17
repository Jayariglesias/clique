CLIQUE JS ALPHA v0.1'

BY: FORDEE -- JAYAR IGLESIAS

LIST OF FUNCTIONS

    -> clique.functionName
    -- Return || Description

    ** append(id,value)
    -- append a value to the id of tags

    ** plusAppend(id,value)
    -- append a value to the id of tags continuously

    ** checkValue(id.value)
    -- return null if null
    -- return value if not null

    ** checkBool(id.value)
    -- return false if null 
    -- return true if not null

    ** checkObject({obj1:value,obj2:value})
    -- return false if 1 object has null
    -- return true if all object has value

    ** setLocal(desiredname,value)
    ** setSession(desiredname,value)
    ** getLocal(nameinserted)
    ** getSession(nameinserted)
    -- return true if success
    -- return true if not success 

    ** setCookie(desiredname,value,hourexpiry)
    -- Ex. setCookie('token','tok_080397', 24)
    ** getCookie(nameinserted)

    ** formatDate(datetime from MySQL)
    -- return 2020-08-03 YYYY-MM-DD 

    ** previewImage(this,idofimgsrc)
    -- put this function in onchange on input file type 
    -- Ex. <input type="file" onchange="previewImage(this,'idofimgsrc') />"

    ** onMousempve(containerid,imgyouwanttomoveid)
    -- allow to move image when mouse is moving

    ** toggle(idofcontainertohide, classnametoremove)
    -- allow to remove/add classname
