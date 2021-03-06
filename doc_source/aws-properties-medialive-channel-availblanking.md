# AWS::MediaLive::Channel AvailBlanking<a name="aws-properties-medialive-channel-availblanking"></a>

Configures the ad avail blanking feature in SCTE\-35 message processing\. This feature blanks out the content for an SCTE\-35 message that is considered an ad avail\. This element belongs to EncoderSettings\.

## Syntax<a name="aws-properties-medialive-channel-availblanking-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-medialive-channel-availblanking-syntax.json"></a>

```
{
  "[AvailBlankingImage](#cfn-medialive-channel-availblanking-availblankingimage)" : InputLocation,
  "[State](#cfn-medialive-channel-availblanking-state)" : String
}
```

### YAML<a name="aws-properties-medialive-channel-availblanking-syntax.yaml"></a>

```
  [AvailBlankingImage](#cfn-medialive-channel-availblanking-availblankingimage): 
    InputLocation
  [State](#cfn-medialive-channel-availblanking-state): String
```

## Properties<a name="aws-properties-medialive-channel-availblanking-properties"></a>

`AvailBlankingImage`  <a name="cfn-medialive-channel-availblanking-availblankingimage"></a>
Blanking image to be used\. Leave empty for solid black\. Only bmp and png images are supported\.  
*Required*: No  
*Type*: [InputLocation](aws-properties-medialive-channel-inputlocation.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`State`  <a name="cfn-medialive-channel-availblanking-state"></a>
When set to enabled, causes video, audio and captions to be blanked when insertion metadata is added\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)