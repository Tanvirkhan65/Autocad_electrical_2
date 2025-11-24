# Autocad_electrical_2
## class-1 == 
            # autocad electrical interface (2d/3d drafting and annotation),
            # ctrl+9(command window remove and back),
            # ctrl+0(make screen big),
            # quick access toolbar,quick access toolbar classic menubar
            # op(option)
            # op(cross hair,selection(grip size)
            # view(viewcube)
            # viewport control workspace (-) 
            # view control
            # viewport control,view controls,visual style control
            # orthomode on (make line straight)
            # polar tracking(angle line tracking )

## class-2 ==
            # circle
            # line
            # pan
            # zoom comand all,object
            # object snap
            # regen
            # erase
            # move
## class-3 == 
            # construction line(horizontal,verticle,angle,bisect,offset(through))
            # ray
            # units
## class-4 == 
            # ARC
            # MOVE 
            # COPY(ARRAY)
            # TRIM,EXTEND,MIRROR
            # POLYLINE(HALFWIDTH,WIDTH,ARC(RADIOUS),
            # POLYGON(inscribed, circumscribed)  note if panel nut m6 then hole should 6.5,m6 head 10mm,washer spring,plane thickness(1.2,1.3),washer dia 10/12
            # spline(control vertex,fit)
## class-5 ==
            # Rectangle(point,dimentions,Area,Rotation)
            # Rect(area,fillet,chamfer,thickness,width,elevation)
            # Rotate(referance,point,copy)
## class-6 ==
            # Point,Multiple point,point style
            # Divide(always ask segment)
            # Measure(always ask length of segment)
            # Scale(copy,referance,point)
            # Strech (full selection move,half selection strech)
## class-7 == 
            # Fillet(pollyline,radius,Trim,Multiple)
            # Chamfer(polyline,distance,angle,Trim,method(distance,angle same as outside),multiple)
            # Blend curves(join to spline smoothly) edit vertex (add,delete)
            # Lengthen(Delta,Percent,Total,Dynamic) lengthen only valid for line
            # Break(break with point)
            # Break at point
            # Align (in modify tool)
            # whipeout(Frames,polyline)
## class-8 ==
            # Properties toolbar(color,lineweight,linetype,line scale,,match properties,list,transperancy)
## class-9 == 
            # utilities tools-> 
            # mesure(quick,distance,angle,radius,area,volume)
            # select all
            # id point,point style
            # quick select
            # ctrl+z undo,ctrl+redo
## class-10 == 
            # single line text(properties all option try)editing option limited
            # multiline all text editing option available like msword 
            # convert single line text to multiline text(express tool -> convert to mtext)
            # convert multi line text to single line text (simplty using explode)
## class-11 == 
            # Array rectangular array (column size,spacecing,row size spaceing)
            # only row have incremental elevation(shift+pan) isometric view -> incremental elevation we only change distance
            # incremental elevation have level for level we use how many level we need and space between level
            # Array base point transfer
            # associtive(array by default associative),for dissociative we should use explode
            # associative array only can use in array edit 
            
             array Edit 
             
            # source source change reflect whole array after change source we need to put command arrayclose
            # replace(if base point select array default base point then object move and replace )  
            if base point select source base point then which array element selected this one only change.
            if select source object then entire array change

            polar array
            # for circular path array(items,fill angle,fill angle between distance,rotate items)
## class-12 == layer
            # 0 layer and dimention def layer bydefault cant edit cant change 
            (o layer,def layer,current layer,yref layer,layer containing object cant delete)
            # layer on,off,lock,print off,line weight,linetype,transperancy
            # layer states manager import export
            # layer filter,group filter
## class-13 == 
            # annotate(center mark)
            # give all dimention 
            Linear
            Aligned
            Angular 
            Arc Length 
            Radius
            Diameter
            Ordinate 
            (Leader, Add Leader, Remove Leader) 
            (Measure)
## class-14 == 
            # dimention style
            # line,symbols & arrows,text, fit,primary units,alternate unit,tolerance
            # important unit-> mesurement scale(if dimention 100 in drawing its multiply by factor and showing multiply value )
            # important FIT-> scale for dimention features > USE OVERALL SCALE OF If the dimention value 100 its not change but its getting bigger by multiply of factor setting
            # important alternate units
            # tolerance command (TOL)
            # style override (minor change in whole style)
## class-15 ==
            # Table,Table style
            # for multiple table cell select use shift+mouse left
            # insert table data-link from excel imported data will be locked and link with excel file any change in excel reflect to autocad 
            # data extraction before data extraction we must save drwaing. data extraction jobs whatever object drawing we create in autocad all data or perticular selected object data can be extracted from autocad to autocad and autocad to excel.
            # table dimention style for data,header,title->general,text,border
## class-16 == 
            # Block(create block,pick point selection,convert to block
            # convert to block -> source object becomming block
            # retain-> source object is not converted to block but its copy become block
            # delete-> onscreen object will be deleted but the copy of object become block
            # block behavior allowed or not allowed explode,scale/uniform allowed/not allowed
            # block unit inch/mm converted automatic
            # adding hyperlink in block.To see the hyperlink we have to press ctrl+object
            # WBLOCK write block for save file permanent
# class-17 == dynamic block
            # DC design center shortcut
            # TP Toolpalates shortcut
            # dynamic block parameters,actions
# class-18 == attributes,edit attributes
            # ATTRIBUTES NAME FIELD OR INFORMATION FIELD IN DRAWING AUTOMATIC VALUE TAKING
# class-19 == hatch
            # Type, pattern, color, swatch(hatch background),angle,scale,draw order(bring to front,bring to back),selection cycle
            # associative hath automatic change by shape,non associative hatch cant change by shape.
            # create separate hatch, non separate hatch
            # hatch open boundary tolerance(gap tolerance)
            # hatch island detection
            # hatch origin(select origin hatch start from there)
            # hatch boundary (remove or ignore boundary by selected line,polyline,circle etc)
            # gradient haatch
            # express tools -> super hatch custom hatch making with image,href,whipeout,block(important)
# class-20 == External Reference (xref)
            # xref attachment -> can not change the original drawing do somthing on original drawing.
            # xref overlay -> only the changes will be shown to next user.
            # xbind -> from orginal drawing layer,block ,linetype ,dimention style can transfer to second drwaing 
            from second drawing xbind command after transfer what is need 
# class-21 == annotation
            # On screen scale original value remain same but change the screen ratio. for show the effect we need to eneble 3 annotative option bottom of the screen
            1. show annotation object
            2. add scale to annotative object
            3. annotation scale of the current view 
# class-22 == parametric constrain
            # parents child relation if we want 2 line want alawasy be same like 90 the select first line point and second line point then second line 
            point come to first line point connect togather angle 90 degree remain 90 degree always called parametric constrain
            # conincident
            # colinear
            # concentric
            # fix
            # parallel 
            # perpendicular 
            # horizontal
            # vertical
            # tangent
            # smooth 
            # symmetric
            # equal
            # auto constrain -> making object automatic become constrain if we select auto constrain after making object
            # show and hide auto constrain
            # delete constrain
            # express tool -> enclosed in object make circle,slot,rectangle around object,text etc
            # express tool -> ARC aligned text around arc 
## class-23 == dimentional constrain
            # if we add dimentional constrain it will automatic change the dimention of object according to our value
            # one object one dimentinal constrain applied
            # normal dimention convert to dimentional constrain
            # delete constrain
            # infer constrain -> if infer constrain on automatic parametric constrain will be add
            # annotation -> dimention continue,baseline,quick dimention,dimention break,adjust dimention space,dimention dimjogline
            inspect,update,reaasociation,center mark,center line,multi leader,add leader
            # MLINE ->MLSTYLE ADD LINE COLOR,display join ETC,SCALE FOR DISTANCE BETWEEN LINE,double click on multiline open multiline edit tool
## class-24 == PRINT,TCOUNT
            # plot -> plot option
            # TCOUNT -> selected copy object give numbering by order
## class-25 == PROJECT,PROJECT SETTNGS
            # copy settings from project file will define the standard of NFPA,IEC,IEEE ETC
## class-26 == project properties
            # componets -> components tag format -> %F%N%S -> % F COMPONENTS NAME LIKE CB %N COMPONENTS REFERANCE LIKE 203/1C %S sheet
            # project wide update/retag any ching change need to update 
            # wire number %N componet reference
## class-27 ==  (WIRE,TRIM WIRE,WIRE NO,EDIT WIRE NO, MULTIPLE BUS, STRETCH WIRE NO)
            # wire ->wire,wire degree,wire gap,(interconnected components)
            # trim wire
            # multiple bus ->       empty space go horizontal
                                    empty space ho vertical in command f for wire flip
                                    components multiple wire(select point of components and drag)
                                    another multiple bus -> take clable from another multiple buses
            # strech wire -> select wire end location then select wire which one strech
            ## wire numbers
            wire tagging -> to do -> 1.tag new/un number only (only new wire or un number will be tagged)
                                     2.tag all (in drawing all number will be tagged automatically) 
                            wire tag mode -> sequential (by default 1/2/3 like this)
                                             line reference (take from line reference)   
                            format override ->we can change by %f,%n componnets name or components referane
                            use wire layer format override -> wire layer can be override 
                            project wide ->ENTIRE PROJECT
                            drawing wide -> ONLY CURRENT DRAWING
                            individual pick -> INDIVIDUAL SELECTED WIRE 
            ## 3 PHASE 

            ## PLC/IO
            ## EDIT WIRE NUMBER
## class-30 ==  (Create Edit wire Type, Change Convert Wire Type, wire no, Copy Wire No, Copy wire no(in line),delete, move , flip wire no, toggle wire no in line, Wire Sequence, show wire sequence)
            # CREATE WIRE -> WIRE COLOR,SIZE,WIRE NUMBERING,LAYER -> %C_%S (%C FOR COLOR  %S FOR SIZE),Line to convert wire,default wire
            polyline cant be change to wire.
            # delete wire number -> use ACADE electrical delete(select delete wire and select the cable all wire number in cable will be deleted),normal delete have some problem
            in normal autocad delete after delete any component wire gap remain autocad electrical delete wire gap will be closed
            # copy wire number,copy wire number in-line,adjust inline wire/gap
            # move wire number -> normal move number could be place any cable but acade move only working on same cable
            # flip wire number -> flip between cable up down
            # toggle wire number -> 1 press become inline wire number another press become top side wire number
            # scoot,move components
            # wire sequence only work in active project
            # wire sequence show the wire flow
## class-31 == (Scoot, move component, wire no leader, insert wire color/gauge labels, in line wire labels, wire trouble shooting)
            # wire number leader -> cable after wire number select then show the leader
            # wire color/gauge labels -> leader with leader / auto and manual with align
            # inline wire label -> cable color/number can insert
            # insert ladder all option check (important)
            # wire troubleshooting -> show wire,show wire number block origin points,show pointer to wire number
            # check/trace wire for electrically connected or not checking
            # flip wire gap
            # delete wire gap
            # check repair/gap pointer
## class-32 == (Move, scoot, stretch, convert ladder, Add Rung, Revise Ladder, Renumber Ladder)
            # add rung 
            # revise ladder (on going project can modify ladder)
            # renumber ladder referance -> all drawing or drawing wise numbering ladder
            # strech ladder normal strech command
            # scoot for ladder strech
            # ladder is not component so component move not working need to use normal move 
            ### very important 
            every attributes based work should be done in single line text even autocad making lader with text should be single line 
            text otherwise we cant convert it to autocad electrical ladder logic
            autocad electrical database only know single line text
            # convertion tool -> normal line used to make ladder convert to ladder and all line make to wire 
## class-33 ==  (Source & Destination Arrows, Fan IN Source, Fan OUT Destination)
            # source arrow & destination arrow -> wire source and destination in drwing and entire project
            # FAN IN SOURCE/FAN IN OUT CAN SHOW THE MULTIPLE BUS IN SINGLE LINE 
            # Referance only arrow for manual set referance only
## class-34 == (XY Grid setup, Reference no setup, Standard selection)
            # first project setup properties -> drawing format need to enable x-y grid
            # x-y grid ->horizontal to vertical or veritcal to horizontal
## class-35 == Libraries and Standard setup 
            # schematic library setup -> select library first folder select ieee/nfpa
            # schematic icon menu file -> select the same ieee/nfpa
## CLASS-36 == ICON MENU & CATALOG BROWSER
            # brows,scale,search icon,map icon to catalog
## class-37 == Insert Edit Component Dialog Box
            # component tag,description,catalog data,multiple catalog,Breaker rating or rating
## class-38 == Parent & Child Components, Project Specific Catlog Database, Equipment List
            # cross referanceing of relay parent childs
## class-39 == Drawing Audit, Electrical Audit, Update Retag Tool, Toggle No/Nc, Schematic Editing
            # Drawing Audit -> drawing Audit alawys check connection points,wire number,wire connetion,identifier,
            1. Component Tag Errors (ট্যাগ/নেমিং সমস্যা)
                        
                        ডুপ্লিকেট ট্যাগ নাম (যেমন: দুটি relay "K1" নামে)
                        
                        মিসিং ট্যাগ (কোনো symbol আছে কিন্তু tag নেই)
                        
                        Wrong tag format (tag style অনুযায়ী না থাকা)
                        
                        Parent-child tag mismatch
                        
                        Coil এবং contact pair mismatch
                        
                        Unassigned component numbers
                        
                        ✔ ফল: রিপোর্টে দেখাবে কোন ডিভাইস conflict করছে, এবং Fix অপশন দিবে।
                        
                        ✅ 2. Wire Number Errors (ওয়্যার নাম্বার সমস্যা)
                        
                        Duplicate wire number on different nets
                        
                        Wire number missing
                        
                        Wire number overlapping
                        
                        Not following the wire number format
                        
                        Unused wire numbers
                        
                        ✔ Audit আপনাকে পুনরায় wire number update করতে বলবে বা auto-fix করবে।
                        
                        ✅ 3. Wire Connection Errors (কানেকশন সম্পর্কিত ভুল)
                        
                        দুইটা wire physically connected কিন্তু electrically connected না
                        
                        Disconnected wire segments
                        
                        Wire gap বা break
                        
                        Wrong source/destination signal
                        
                        Wire not touching component pins
                        
                        Wire sequence conflict
                        
                        ✔ এগুলো AutoCAD Electrical ইলেক্ট্রিক্যাল error হিসেবে দেখায়।
                        
                        ✅ 4. Block/Symbol Errors (সিম্বল বা ব্লক সমস্যা)
                        
                        Non-electrical block mistakenly placed in schematics
                        
                        Wrong attribute values
                        
                        Missing attributes
                        
                        Required attributes not filled
                        
                        External reference block errors
                        
                        ✔ Audit সাজেশন দেয় attribute update করার।
                        
                        ✅ 5. Project Database Errors (WD_M ডেটাবেস চেক)
                        
                        Drawing database corruption
                        
                        Project database inconsistencies
                        
                        Wrong cross-reference links
                        
                        Report table mismatch
                        
                        ✔ Audit database clean-up করে।
                        
                        ✅ 6. Cross-Reference Errors
                        
                        Coil এবং contact cross-reference ভুল
                        
                        Signal source missing
                        
                        Destination missing
                        
                        Parent and child symbol mismatch
                        
                        ✔ Auto-fix parent/child linking।
                        
                        ✅ 7. Ladder Reference Errors
                        
                        Ladder rung not recognized
                        
                        Wrong ladder reference numbering
                        
                        Missing rung tag
                        
                        Duplicate ladder numbers
                        
                        ✔ Fix Ladder tools ব্যবহার করতে বলে।
                        
                        ✅ 8. Panel Footprint Errors
                        
                        Footprint linked না
                        
                        BOM attribute missing
                        
                        Multi-part component link missing
                        
                        ✔ Audit এই error গুলো দেখায়।
                        
                        ✅ 9. Project Settings/ENV Errors
                        
                        Missing drawing properties
                        
                        Incorrect project settings
                        
                        Wrong template data
                        
                        Environment variables mismatch
                        
                        ✔ এটা সাধারণত বড় প্রজেক্টে ঘটে।
            # electrical Audit
            # toggle no/nc -> NC converted to no swich or reverse
            # wire tag setup
            # schematic edit -> move component,scoot,copy components,Align components,delete component
            # components update from catalog tool
            # surf tool -> # means panel layout symbol,P means parent C means child component
            W means wire/wire related component,src/dst,
            freshen -> refresh
            pick new list,pan
## class-40 == attributes edit
## class-41 == Symbol Builder ,Icon menu Wizard
## class-42 == circuit builder tool
## class-43 == save circuit to icon menu, copy circuit, save & insert w block circuit
## class-44 == Connectors & Customize Connectors, Point to Point Connections
            # insert connector -> insert all,allow spacer or brakes,at wire crossing,start connector as child
            # details -> plug(male) & receptacle pin,plug/receptacle
            # pin list -> alphanumeric or number

