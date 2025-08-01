## Example Documentation
```plain
We have been successfully transitioning from a spaghetti to a more structured architecture with the model in the center, and the logic as an intermediate layer towards the gui which is the outer shell.
There are additional utility packages for preferences and the cli.
...
```

## Example Architecture Component Model (UML)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<uml:Model xmi:version="20131001" xmlns:xmi="http://www.omg.org/spec/XMI/20131001" xmlns:uml="http://www.eclipse.org/uml2/5.0.0/UML" xmi:id="__nu3UEl3Ee243f2e4VWs6w" name="JabRef">
  <packagedElement xmi:type="uml:Component" xmi:id="_EBiwMEl4Ee243f2e4VWs6w" name="cli"/>
  <packagedElement xmi:type="uml:Component" xmi:id="_Coy0kEl4Ee243f2e4VWs6w" name="gui"/>
  <packagedElement xmi:type="uml:Component" xmi:id="_MFIzMEl4Ee243f2e4VWs6w" name="model"/>
  <packagedElement xmi:type="uml:Component" xmi:id="_He3LoEl4Ee243f2e4VWs6w" name="logic"/>
  <packagedElement xmi:type="uml:Component" xmi:id="_KsOfgEl4Ee243f2e4VWs6w" name="globals"/>
  <packagedElement xmi:type="uml:Component" xmi:id="_NUdtEEl4Ee243f2e4VWs6w" name="preferences"/>
</uml:Model>
```

## Example Code Model
```json
{
  "id" : "acm029305jsd",
  "codeItemRepository" : {
    "repository" : {
      "acm001337jsd" : {
        "type" : "CodeCompilationUnit",
        "id" : "acm001337jsd",
        "name" : "Abbreviation",
        "parentId" : "acm001341jsd",
        "content" : [ "acm001355jsd" ],
        "pathElements" : [ "buildSrc", "src", "copied", "java", "org", "jabref", "logic", "journals" ],
        "extension" : "java",
        "language" : "JAVA"
      },
      "acm001338jsd" : {
        "type" : "CodePackage",
        "id" : "acm001338jsd",
        "name" : "org",
        "parentId" : null,
        "content" : [ "acm001339jsd" ]
      },
      "acm001339jsd" : {
        "type" : "CodePackage",
        "id" : "acm001339jsd",
        "name" : "jabref",
        "parentId" : "acm001338jsd",
        "content" : [ "acm021293jsd", "acm001340jsd", "acm001428jsd", "acm001446jsd", "acm001466jsd", "acm001569jsd", "acm017785jsd", "acm017861jsd", "acm020753jsd", "acm029239jsd", "acm029246jsd", "acm029257jsd" ]
      },
      "acm001340jsd" : {
        "type" : "CodePackage",
        "id" : "acm001340jsd",
        "name" : "logic",
        "parentId" : "acm001339jsd",
        "content" : [ "acm010356jsd", "acm010367jsd", "acm010376jsd", "acm022247jsd", "acm001341jsd", "acm010386jsd", "acm010422jsd", "acm010463jsd", "acm010673jsd", "acm010873jsd", "acm011016jsd", "acm011112jsd", "acm011280jsd", "acm011350jsd", "acm011391jsd", "acm011702jsd", "acm011725jsd", "acm012220jsd", "acm012247jsd", "acm012255jsd", "acm012263jsd", "acm014499jsd", "acm014898jsd", "acm014967jsd", "acm015732jsd", "acm015743jsd", "acm015837jsd", "acm015977jsd", "acm016468jsd", "acm016586jsd", "acm016646jsd", "acm016656jsd", "acm016721jsd", "acm016815jsd", "acm016854jsd", "acm017210jsd", "acm017243jsd", "acm017268jsd", "acm017682jsd" ]
      }
    }
  }
}
```

## Example Gold Standard
```csv
sentenceID,codeID
1,buildSrc/src/copied/java/org/jabref/logic/
1,src/main/java/org/jabref/gui/
1,src/main/java/org/jabref/logic/
1,src/main/java/org/jabref/model/
1,src/test/java/org/jabref/gui/
1,src/test/java/org/jabref/logic/
1,src/test/java/org/jabref/model/
2,src/main/java/org/jabref/cli/
2,src/main/java/org/jabref/preferences/
2,src/test/java/org/jabref/cli/
4,buildSrc/src/copied/java/org/jabref/logic/
4,src/main/java/org/jabref/gui/
4,src/main/java/org/jabref/logic/
4,src/main/java/org/jabref/model/
4,src/test/java/org/jabref/gui/
4,src/test/java/org/jabref/logic/
4,src/test/java/org/jabref/model/
5,src/main/java/org/jabref/model/
5,src/test/java/org/jabref/model/
6,buildSrc/src/copied/java/org/jabref/logic/
6,src/main/java/org/jabref/gui/
6,src/main/java/org/jabref/logic/
6,src/main/java/org/jabref/model/
6,src/test/java/org/jabref/gui/
6,src/test/java/org/jabref/logic/
6,src/test/java/org/jabref/model/
7,src/main/java/org/jabref/gui/
7,src/test/java/org/jabref/gui/
9,buildSrc/src/copied/java/org/jabref/logic/
9,src/main/java/org/jabref/logic/
9,src/main/java/org/jabref/model/
9,src/test/java/org/jabref/logic/
9,src/test/java/org/jabref/model/
10,src/main/java/org/jabref/cli/
10,src/test/java/org/jabref/cli/
11,src/main/java/org/jabref/preferences/
12,src/main/java/org/jabref/model/
12,src/test/java/org/jabref/model/
```
