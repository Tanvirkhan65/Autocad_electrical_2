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
