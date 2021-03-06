# AWS::ElasticLoadBalancingV2::Listener Certificate<a name="aws-properties-elasticloadbalancingv2-listener-certificate"></a>

Specifies an SSL server certificate to use as the default certificate for a secure listener\.

## Syntax<a name="aws-properties-elasticloadbalancingv2-listener-certificate-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-elasticloadbalancingv2-listener-certificate-syntax.json"></a>

```
{
  "[CertificateArn](#cfn-elasticloadbalancingv2-listener-certificate-certificatearn)" : String
}
```

### YAML<a name="aws-properties-elasticloadbalancingv2-listener-certificate-syntax.yaml"></a>

```
  [CertificateArn](#cfn-elasticloadbalancingv2-listener-certificate-certificatearn): String
```

## Properties<a name="aws-properties-elasticloadbalancingv2-listener-certificate-properties"></a>

`CertificateArn`  <a name="cfn-elasticloadbalancingv2-listener-certificate-certificatearn"></a>
The Amazon Resource Name \(ARN\) of the certificate\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)