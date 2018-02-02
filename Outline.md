# My Outline

Step 1  
Next line

Step 2

## Second heading

Operational intelligence
Configure an instance to monitor a server
Simulate high CPU usage.
Have the student instances create an incident.

> Quote

**Bold**
*Italics*

---
Horizontal line

Lists
 - Item 1
 - Item 2
 - Item 3
 
 Link [Google](http://www.google.com)

```javascript
gs.eventQueue("discovery.phase.complete", current);
checkNextPhaseOrComplete();

function checkNextPhaseOrComplete() {
    var dp = new DiscoveryPhaser(current);
    if (dp.hasNextPhase())
        return;

    current.state = "Completed";
    current.update();
    var d = new Discovery();
    d.completed();
}
```

![alt text](https://github.com/jonokoster/CC18/raw/master/images/Image1.png "Logo Title Text 1")

<kbd>
  <img src="https://github.com/jonokoster/CC18/raw/master/images/Image1.png">
</kbd>