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

## Example Gold Standard
```csv
modelElementID,sentence
_MFIzMEl4Ee243f2e4VWs6w,2
_He3LoEl4Ee243f2e4VWs6w,2
_Coy0kEl4Ee243f2e4VWs6w,2
_MFIzMEl4Ee243f2e4VWs6w,5
_He3LoEl4Ee243f2e4VWs6w,6
```
