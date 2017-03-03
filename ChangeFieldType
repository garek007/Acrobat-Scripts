var fieldTypeToChange = "signature";
var newFieldType = "text";

for (var fieldNumber = 0; fieldNumber  < numFields; fieldNumber ++)
{
  var thisField = getField(getNthFieldName(fieldNumber));    
  if(thisField.type == fieldTypeToChange){
    var aRect = thisField.rect;
    var newField = addField(thisField.name+"fieldNumber", newFieldType, thisField.page, aRect);
    removeField(thisField.name);

  }
}
