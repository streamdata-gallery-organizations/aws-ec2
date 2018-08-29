{
  "info": {
    "name": "AWS EC2 API Describe Subnets",
    "_postman_id": "9967204b-b008-4661-bb9f-4f726e710e20",
    "description": "Describes one or more of your subnets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "afe05b55-7995-42c0-917f-6887d647316f",
          "name": "describeaccountattributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountAttributes?ClientToken=ClientToken&Description=Description&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&Name=Name&SourceImageId=SourceImageId&SourceRegion=SourceRegion",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes attributes of your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c4180a3-400f-4515-8e10-cf657943b630"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "7bee327e-dbe9-4815-b39b-8028812d6439",
          "name": "copyimage",
          "request": {
            "url": "http://example.com/api/?Action=CopyImage?BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&InstanceId=InstanceId&Name=Name&NoReboot=NoReboot",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the copy of an AMI from the specified source region to the current region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da273bf4-cb71-4411-8df7-4ef8eb99707c"
            }
          ]
        },
        {
          "id": "640cad72-7596-4386-b0ee-aceebb6a9397",
          "name": "createimage",
          "request": {
            "url": "http://example.com/api/?Action=CreateImage?DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is either running or stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d071cda7-580d-41f8-87bd-53816838637b"
            }
          ]
        },
        {
          "id": "ff22e77f-09fe-49df-bcc6-e101fe0bee1e",
          "name": "deregisterimage",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a4b6a1d-0c60-4b8e-ac31-de6b6d21ada8"
            }
          ]
        },
        {
          "id": "f06ae7d3-d56c-4db4-8c5c-ad4ef7c34ca1",
          "name": "describeimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImageAttribute?DryRun=DryRun&ExecutableBy.N=ExecutableBy.N&Filter.N=Filter.N&ImageId.N=ImageId.N&Owner.N=Owner.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "012121ea-f0e3-4c3a-bacb-b355fe5a4af8"
            }
          ]
        },
        {
          "id": "65e081e4-05d6-4b71-bd87-d0efa0169d41",
          "name": "describeimages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Attribute=Attribute&Description=Description&DryRun=DryRun&ImageId=ImageId&LaunchPermission=LaunchPermission&OperationType=OperationType&ProductCode.N=ProductCode.N&UserGroup.N=UserGroup.N&UserId.N=UserId.N&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the images (AMIs, AKIs, and ARIs) available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a68543dc-9b86-4401-b74a-b37b35824cdc"
            }
          ]
        },
        {
          "id": "291b793d-b1fb-447f-ad5d-9a6b403bffad",
          "name": "modifyimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyImageAttribute?Architecture=Architecture&BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&EnaSupport=EnaSupport&ImageLocation=ImageLocation&KernelId=KernelId&Name=Name&RamdiskId=RamdiskId&RootDeviceName=RootDeviceName&SriovNetSupport=SriovNetSupport&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d17094ca-b48f-4cf0-98d1-b4f0e8682573"
            }
          ]
        },
        {
          "id": "ee1ac4a3-8142-4253-acb4-4f78c071ddbe",
          "name": "registerimage",
          "request": {
            "url": "http://example.com/api/?Action=RegisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f230722e-922e-49e3-8c59-54b021d729d8"
            }
          ]
        },
        {
          "id": "26a85709-5d1c-4d01-82d1-086fe6e1a99a",
          "name": "resetimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetImageAttribute?DryRun=DryRun&InstanceId=InstanceId&ProductCode=ProductCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an AMI to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0684c938-28d3-4fef-9333-90db2158d0ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "a3a98806-bdd0-4a3a-91b5-4996f1863cc5",
          "name": "confirmproductinstance",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmProductInstance?DryRun=DryRun&InstanceId=InstanceId&Storage=Storage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Determines whether a product code is associated with an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a43685d0-604e-4c6e-8f68-4cd55bc6472d"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "1cbdd6a9-a98c-4a8b-8406-953e646fce53",
          "name": "bundleinstance",
          "request": {
            "url": "http://example.com/api/?Action=BundleInstance?BundleId=BundleId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Bundles an Amazon instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3fde016-78df-43c5-903c-cc2b504adba1"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "2352352f-44fa-4b2f-b762-63a8d9417bfd",
          "name": "cancelbundletask",
          "request": {
            "url": "http://example.com/api/?Action=CancelBundleTask?BundleId.N=BundleId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a bundling operation for an instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8622855f-912f-4534-98a3-c336eeea4a6e"
            }
          ]
        },
        {
          "id": "1face255-3c5c-4536-965d-ff7530eb2323",
          "name": "describebundletasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBundleTasks?DryRun=DryRun&InstanceId=InstanceId&SecurityGroupId.N=SecurityGroupId.N&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your bundling tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94731100-3105-4786-b33a-83c2d6ba91f7"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "eab37818-4838-44f7-9eac-cbbea2e41c5c",
          "name": "attachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=AttachClassicLinkVpc?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more of the VPC's\n\t\t\tsecurity groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cecc6550-ec81-4326-b764-b8b25d8c2716"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "0bb341ff-b609-4a5f-9e8b-f9c44e909f28",
          "name": "describeclassiclinkinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeClassicLinkInstances?DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your linked EC2-Classic instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8eaf7d68-5291-43ac-b1c6-ef24d3dd4dfe"
            }
          ]
        },
        {
          "id": "761b6a9b-32b5-4580-b9e8-3f87298772e9",
          "name": "modifyinstanceplacement",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstancePlacement?ClientToken=ClientToken&CurrencyCode=CurrencyCode&HostIdSet.N=HostIdSet.N&LimitPrice=LimitPrice&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set the instance affinity value for a specific stopped instance and modify the\n            instance tenancy setting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15f5f715-518d-4e99-a7bf-f87f09c1dd2f"
            }
          ]
        },
        {
          "id": "20c087f2-ff62-49cb-911f-43dc028cb6aa",
          "name": "describeinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceAttribute?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f021b769-9d77-48c9-92a0-7674509a648c"
            }
          ]
        },
        {
          "id": "221490bb-6d63-4330-b8b9-73d76e01d277",
          "name": "describeinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?DryRun=DryRun&Filter.N=Filter.N&IncludeAllInstances=IncludeAllInstances&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9ffd5bb-b2ab-4a74-a06a-1b3a47f2ebaf"
            }
          ]
        },
        {
          "id": "564e46b2-9654-48cf-8fe8-70679e2fe9c8",
          "name": "modifyinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstanceAttribute?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "463089d4-0b10-4309-b55e-ad53ddbb0d1a"
            }
          ]
        },
        {
          "id": "89e54543-7ad0-471b-8f85-cb54fed3152d",
          "name": "reportinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=ReportInstanceStatus?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits feedback about the status of an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ddc5198e-adf6-421c-9e6f-0dae59ee4736"
            }
          ]
        },
        {
          "id": "6f716a9a-5e85-4498-8660-45cfc34acd5f",
          "name": "resetinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetInstanceAttribute?AdditionalInfo=AdditionalInfo&BlockDeviceMapping.N=BlockDeviceMapping.N&ClientToken=ClientToken&DisableApiTermination=DisableApiTermination&DryRun=DryRun&EbsOptimized=EbsOptimized&IamInstanceProfile=IamInstanceProfile&ImageId=ImageId&InstanceInitiatedShutdownBehavior=InstanceInitiatedShutdownBehavior&InstanceType=InstanceType&Ipv6Address.N=Ipv6Address.N&Ipv6AddressCount=Ipv6AddressCount&KernelId=KernelId&KeyName=KeyName&MaxCount=MaxCount&MinCount=MinCount&Monitoring=Monitoring&NetworkInterface.N=NetworkInterface.N&Placement=Placement&PrivateIpAddress=PrivateIpAddress&RamdiskId=RamdiskId&SecurityGroup.N=SecurityGroup.N&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId&UserData=UserData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an instance to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a56c3fc-7d38-4b1d-834e-f394dbd19fbd"
            }
          ]
        },
        {
          "id": "14008eba-071a-4612-961c-b9633359be71",
          "name": "unmonitorinstances",
          "request": {
            "url": "http://example.com/api/?Action=UnmonitorInstances?DryRun=DryRun&InternetGatewayId=InternetGatewayId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables detailed monitoring for a running instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3d5e211-93b7-42c8-8925-eb027522b1da"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "f0574a43-d072-4911-ac86-e999c9eb5756",
          "name": "describevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLink?MaxResults=MaxResults&NextToken=NextToken&VpcIds.N=VpcIds.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa26f772-0b69-4a5c-92a5-a8451852f8e3"
            }
          ]
        },
        {
          "id": "669f4194-1473-4d85-be6a-e1f2e0528820",
          "name": "detachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=DetachClassicLinkVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks (detaches) a linked EC2-Classic instance from a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2237619-a7cd-44c3-8fc0-946a0d78f15c"
            }
          ]
        },
        {
          "id": "45e37ac8-d98d-42cb-8801-48212f03f9c5",
          "name": "disablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d84fd568-3a92-42e2-acbe-65c8a5e971d2"
            }
          ]
        },
        {
          "id": "77a0a9f5-c922-4518-beb9-03ea1c714a3d",
          "name": "enablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5379c521-66d0-40d2-b4cf-19f3222a6a4a"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "b2ae8b1e-7796-427f-a44f-a1d963b5b596",
          "name": "describevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLinkDnsSupport?DryRun=DryRun&InstanceId=InstanceId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink DNS support status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f3f4459-d8ed-4b54-b9d5-e0d714ad4ae4"
            }
          ]
        },
        {
          "id": "c91cdeae-c474-4194-9334-29b1b3123c40",
          "name": "disablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLinkDnsSupport?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink DNS support for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18c95a56-f299-4278-be1b-6f28bc9b7abb"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "c95b0927-c015-4163-a216-ad0c95e64d47",
          "name": "enablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLinkDnsSupport?BgpAsn=BgpAsn&DryRun=DryRun&IpAddress=IpAddress&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC to support DNS hostname resolution for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af77eba4-b1e1-4457-8a9f-b81e0b6eaa54"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "f449f16f-53b6-49a3-b66a-88775e65d56c",
          "name": "createcustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateCustomerGateway?CustomerGatewayId=CustomerGatewayId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information to AWS about your VPN customer gateway device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0e72db4-339c-42c4-a232-e4c3d59bd6e5"
            }
          ]
        },
        {
          "id": "1747fed4-ac97-4741-af91-497ec74a8b97",
          "name": "createnatgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateNatGateway?NatGatewayId=NatGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a NAT gateway in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "beadf1a8-2f6a-4ba3-9288-4dd2f62ecfe3"
            }
          ]
        },
        {
          "id": "c3cb9a72-77c9-4d3c-bf14-caf5823cbc93",
          "name": "deletenatgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNatGateway?Filter.N=Filter.N&MaxResults=MaxResults&NatGatewayId.N=NatGatewayId.N&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified NAT gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85449d81-6f12-47bb-9050-6ba40db45fce"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "3ae2de1c-2933-4884-baa8-69cdd217f7e6",
          "name": "deletecustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCustomerGateway?CustomerGatewayId.N=CustomerGatewayId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified customer gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c351d3af-0377-4100-ba79-4111b2d523ab"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "f8b56935-2a8c-4979-8638-76db4dfb25e8",
          "name": "describecustomergateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCustomerGateways?AutoPlacement=AutoPlacement&AvailabilityZone=AvailabilityZone&ClientToken=ClientToken&InstanceType=InstanceType&Quantity=Quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPN customer gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5792740-7167-45b3-857c-927e1548c840"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "ad62127c-ab59-4288-bfe5-81d02b1176b7",
          "name": "allocatehosts",
          "request": {
            "url": "http://example.com/api/?Action=AllocateHosts?Filter.N=Filter.N&HostId.N=HostId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allocates a Dedicated Host to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98198153-4d64-4b3b-9e30-529dcfdc970c"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "1ed681f4-138a-46c3-bf5f-c8804b02c94b",
          "name": "describehosts",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHosts?Filter.N=Filter.N&MaxDuration=MaxDuration&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Dedicated Hosts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99346c92-1188-4f83-aa24-df347fdc7185"
            }
          ]
        },
        {
          "id": "f78700de-f541-40df-b96f-677a71948d59",
          "name": "modifyhosts",
          "request": {
            "url": "http://example.com/api/?Action=ModifyHosts?Affinity=Affinity&HostId=HostId&InstanceId=InstanceId&Tenancy=Tenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modify the auto-placement setting of a Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2051d76-0b50-4242-9bb4-70630190cb8c"
            }
          ]
        },
        {
          "id": "70849dcb-3d21-4a7b-9bba-7337bd55afb3",
          "name": "releasehosts",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseHosts?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "When you no longer want to use an On-Demand Dedicated Host it can be released."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3bb8f976-86b8-4ea7-be07-ef4fb01835e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "6460d246-fd2b-4a9d-bae1-e3f5d1c71402",
          "name": "describehostreservationofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservationOfferings?Filter.N=Filter.N&HostReservationIdSet.N=HostReservationIdSet.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Dedicated Host Reservations that are available to purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e13b2987-4028-4e54-86e6-2e12b656d6bc"
            }
          ]
        },
        {
          "id": "adb9c0f9-28f1-42bd-8105-c2cc7adf9075",
          "name": "describehostreservations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservations?HostIdSet.N=HostIdSet.N&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Dedicated Host Reservations which are associated with Dedicated Hosts in\n            your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf3c7728-2bec-42f1-9f05-0b1cce2eae64"
            }
          ]
        },
        {
          "id": "08fde719-6706-4047-afa8-9a657d227250",
          "name": "gethostreservationpurchasepreview",
          "request": {
            "url": "http://example.com/api/?Action=GetHostReservationPurchasePreview?AutoPlacement=AutoPlacement&HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Preview a reservation purchase with configurations that match those of your\n            Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13ab8c58-653c-4289-89e0-76ccb51fd467"
            }
          ]
        },
        {
          "id": "2df5670f-5731-4886-9a58-bb61ff2c45a8",
          "name": "purchasehostreservation",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseHostReservation?HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchase a reservation with configurations that match those of your Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77235084-663d-4212-a93a-d55a4d322d69"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "94474713-f09b-449c-8a3c-3cc5224e8fac",
          "name": "associatedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=AssociateDhcpOptions?DhcpConfiguration.N=DhcpConfiguration.N&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a set of DHCP options (that you've previously created) with the specified VPC, or associates no DHCP options with the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92f029fe-1994-42c2-b4fb-bbc79b1bdce7"
            }
          ]
        },
        {
          "id": "0ffeb5a7-684f-4c74-ae77-4c1a647905b5",
          "name": "createdhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=CreateDhcpOptions?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a set of DHCP options for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c19d250d-86d2-44a8-9714-cbb71042315d"
            }
          ]
        },
        {
          "id": "fbd1948a-1c99-492d-bd62-5a663b6525a6",
          "name": "deletedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDhcpOptions?DhcpOptionsId.N=DhcpOptionsId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified set of DHCP options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f98b41ac-40e1-4622-b6aa-ca1b7bb6c38d"
            }
          ]
        },
        {
          "id": "9bbee8c7-37c0-4a10-a74b-0c3258288361",
          "name": "describedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDhcpOptions?Device=Device&DryRun=DryRun&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your DHCP options sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbe277ca-feb4-4e8f-b14a-deb35bb00898"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "152c8473-d675-4008-b31a-4873b7d55838",
          "name": "attachvolume",
          "request": {
            "url": "http://example.com/api/?Action=AttachVolume?Description=Description&DestinationRegion=DestinationRegion&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&PresignedUrl=PresignedUrl&SourceRegion=SourceRegion&SourceSnapshotId=SourceSnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an EBS volume to a running or stopped instance and exposes it to the instance with\n      the specified device name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9881248b-87d5-426b-8dd4-3d4705f12f68"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "4189e053-3f48-4f2c-91ab-0714388ff6bd",
          "name": "copysnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CopySnapshot?Description=Description&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a31575c9-85ec-4da7-a5a8-a71349f07626"
            }
          ]
        },
        {
          "id": "b0f1046d-5e59-4ca9-b4a3-dc56ab4c2253",
          "name": "describesnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&Owner.N=Owner.N&RestorableBy.N=RestorableBy.N&SnapshotId.N=SnapshotId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77069875-2bc4-4130-8981-74d7f63d134f"
            }
          ]
        },
        {
          "id": "0dd61d4e-2b86-4b32-93cd-9ef1d9fb4ccb",
          "name": "describesnapshots",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshots?Attribute=Attribute&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the EBS snapshots available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63831def-d99b-41d1-adda-b6272818da77"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "b6b4ec18-f359-4639-959a-a0f76d2bd2e8",
          "name": "createsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Encrypted=Encrypted&Iops=Iops&KmsKeyId=KmsKeyId&Size=Size&SnapshotId=SnapshotId&VolumeType=VolumeType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "707f6c33-f1ce-4206-a2f2-532b2cc4989a"
            }
          ]
        },
        {
          "id": "9df8d782-a8af-4c99-ac83-b8280bcdb102",
          "name": "deletesnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshot?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26fdaae3-d98c-4979-8b27-0034fb4c5b54"
            }
          ]
        },
        {
          "id": "81af3a2e-0856-4ab5-8d7c-cf0a27d36435",
          "name": "modifysnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifySnapshotAttribute?AutoEnableIO=AutoEnableIO&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or removes permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fef362db-c705-4f66-8bd6-8e944294a852"
            }
          ]
        },
        {
          "id": "ac6d6db7-859d-4f2c-a2cb-0214b54c81c6",
          "name": "resetsnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetSnapshotAttribute?Domain=Domain&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd4e246e-e064-484d-beee-d197309e5db9"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "205a04d6-110f-418d-9d3c-eb574e9a74b4",
          "name": "createvolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateVolume?DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an EBS volume that can be attached to an instance in the same Availability Zone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9997e62-c435-4cbc-8e4b-3cff9133e57f"
            }
          ]
        },
        {
          "id": "abc90c2b-178d-4813-851c-15e11f16309d",
          "name": "deletevolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "179d6571-76d5-4421-ae90-e8dae5e5dde1"
            }
          ]
        },
        {
          "id": "d345ed93-e6a4-4cc2-8d50-f0d7557971be",
          "name": "detachvolume",
          "request": {
            "url": "http://example.com/api/?Action=DetachVolume?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an EBS volume from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64c9e47a-1215-46fe-a497-7bdac63e64f1"
            }
          ]
        },
        {
          "id": "7a2ec831-9fb7-4aba-8c87-d4e786312c4d",
          "name": "modifyvolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVolumeAttribute?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies a volume attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2efa0ce0-abd0-4119-b8ba-e74c4d5dd3ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "35c0d204-a0c9-424a-8331-9b8397db3238",
          "name": "describevolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f4fc759-5c36-4c09-85ce-b3637a464023"
            }
          ]
        },
        {
          "id": "0406ce72-12e6-4932-af50-d3dee8111340",
          "name": "describevolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumes?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified EBS volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6775da4-e7c6-475d-9698-f21a5c789abe"
            }
          ]
        },
        {
          "id": "4c7f42d0-b17d-4446-b95f-1660f3f1148b",
          "name": "enablevolumeio",
          "request": {
            "url": "http://example.com/api/?Action=EnableVolumeIO?Attribute=Attribute&CreateVolumePermission=CreateVolumePermission&DryRun=DryRun&OperationType=OperationType&SnapshotId=SnapshotId&UserGroup.N=UserGroup.N&UserId.N=UserId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables I/O operations for a volume that had I/O operations disabled because the data on the\n      volume was potentially inconsistent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74409407-361d-40cd-9b60-20f0ff167f73"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "ee572044-558d-4a17-9299-771cec705900",
          "name": "describevolumestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeStatus?Device=Device&DryRun=DryRun&Force=Force&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of the specified volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86debfb2-e1cf-43d3-86f7-a446a593cf6f"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "477f7403-c69b-4a51-8348-7b473c03e901",
          "name": "allocateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AllocateAddress?AllocationId=AllocationId&AllowReassociation=AllowReassociation&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress=PrivateIpAddress&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Acquires an Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3296d366-506c-4f27-8362-6e266c2384ca"
            }
          ]
        },
        {
          "id": "887d3ecb-4c9d-49bc-8bf7-1332c49740ad",
          "name": "associateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AssociateAddress?AllocationId.N=AllocationId.N&DryRun=DryRun&Filter.N=Filter.N&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates an Elastic IP address with an instance or a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18cd3f3b-e90e-4887-9646-99a5b1316bc0"
            }
          ]
        },
        {
          "id": "cb1cec57-e8cf-46a0-8a16-39025f6f376b",
          "name": "describemovingaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMovingAddresses?AssociationId=AssociationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Elastic IP addresses that are being moved to the EC2-VPC platform, or that are being restored to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a86028bf-00b5-4ca5-ac44-0ff804f6bd3a"
            }
          ]
        },
        {
          "id": "bf0df15d-4607-48d5-9cd7-22b8b2e3b021",
          "name": "moveaddresstovpc",
          "request": {
            "url": "http://example.com/api/?Action=MoveAddressToVpc?AllocationId=AllocationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ce96793-91de-48af-a4a3-4153f6feb6c8"
            }
          ]
        },
        {
          "id": "785ff273-6c7e-43de-a025-9178afce7402",
          "name": "releaseaddress",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Releases the specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c25199c-0c0b-46da-b0fa-024397bdeb21"
            }
          ]
        },
        {
          "id": "a2312d6b-f16d-4f99-8944-d975b93da1db",
          "name": "assignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignIpv6Addresses?AllowReassignment=AllowReassignment&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more IPv6 addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20a03e20-3761-470a-aca6-1b8ee0cb0ec3"
            }
          ]
        },
        {
          "id": "890cf50a-8db8-4566-8a47-43472fc39271",
          "name": "assignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignPrivateIpAddresses?DeviceIndex=DeviceIndex&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more secondary private IP addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4106cdc3-a66e-4419-a76c-2ba357b622a9"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "0715ad31-860e-4d42-a403-b5b91fd0d38c",
          "name": "describeaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAddresses?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Elastic IP addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2607858-2262-47e4-8f68-e5397baefb09"
            }
          ]
        },
        {
          "id": "c0031c1d-ee20-415d-9432-517382360223",
          "name": "restoreaddresstoclassic",
          "request": {
            "url": "http://example.com/api/?Action=RestoreAddressToClassic?Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Restores an Elastic IP address that was previously moved to the EC2-VPC platform back to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5371784e-f64d-4de5-b648-e56a3533f59a"
            }
          ]
        },
        {
          "id": "50df7db4-7312-44dd-b1d7-8f1e918b299e",
          "name": "unassignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignPrivateIpAddresses?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more secondary private IP addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e64af68-c545-48f7-9bb0-8225379b302c"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "3f7306d1-fcb0-4086-bd32-a89c719d95e0",
          "name": "disassociateaddress",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates an Elastic IP address from the instance or network interface it's associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80a202f1-9f00-4615-84c8-18db5fb62038"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "e843726f-0171-4eb0-ba85-347df915ff52",
          "name": "attachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=AttachNetworkInterface?Description=Description&DryRun=DryRun&Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&PrivateIpAddress=PrivateIpAddress&PrivateIpAddresses.N=PrivateIpAddresses.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a network interface to an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32dff390-6bf7-497d-a768-4d9dd1b8eaf4"
            }
          ]
        },
        {
          "id": "5dda49d2-3290-4e3d-8e5e-080abcf58663",
          "name": "createnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkInterface?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network interface in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e24ae181-dbc6-40d1-bc86-a0a8500b64bb"
            }
          ]
        },
        {
          "id": "0e7ed14e-e476-4bcb-8d8a-e16ee1239ccb",
          "name": "deletenetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkInterface?Attribute=Attribute&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc416b2b-fbf8-41b2-a7d8-53179ed7aff0"
            }
          ]
        },
        {
          "id": "eeca1945-d529-4fa9-8c54-692f28182698",
          "name": "describenetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaceAttribute?DryRun=DryRun&Filter.N=Filter.N&NetworkInterfaceId.N=NetworkInterfaceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ce058b0-af59-4fbb-884f-c9a568b55520"
            }
          ]
        },
        {
          "id": "c7d04ccf-a2b1-4b14-9bd9-c66cedc04643",
          "name": "describenetworkinterfaces",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaces?AttachmentId=AttachmentId&DryRun=DryRun&Force=Force",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network interfaces."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "632e1085-1653-4b57-a418-fc888da036fa"
            }
          ]
        },
        {
          "id": "74b49be7-0852-4b3a-96fb-d17a368e282b",
          "name": "detachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DetachNetworkInterface?Attachment=Attachment&Description=Description&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SecurityGroupId.N=SecurityGroupId.N&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a network interface from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19888a36-7b6b-4bb3-afd9-73ab245afa9a"
            }
          ]
        },
        {
          "id": "49dd3818-d4eb-4190-b7c5-31bb48e744d4",
          "name": "modifynetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyNetworkInterfaceAttribute?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18a4475b-25e4-48cf-98f1-343a36b95c8f"
            }
          ]
        },
        {
          "id": "08119fb2-9eb6-42df-980b-02a06f6749e8",
          "name": "resetnetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetNetworkInterfaceAttribute?Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "195cfc65-cd9c-42ae-891e-ca19ea81e4bb"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "6cde8476-c82f-4918-8c4c-c3688874cfeb",
          "name": "unassignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignIpv6Addresses?NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more IPv6 addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60b511d6-0d41-4ca6-b7bf-5d0b41f92960"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "b48c3851-c463-4906-aa05-f0e5c027f851",
          "name": "describeinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceStatus?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d1a5c24-de56-4e2d-be2f-0efc987c9eb8"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "db48137b-f32e-4fe2-b48d-f8f633c94541",
          "name": "getconsoleoutput",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleOutput?DryRun=DryRun&InstanceId=InstanceId&WakeUp=WakeUp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the console output for the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21bb37eb-fecb-4995-9ec0-b297bdc1c188"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "41a83fe9-000b-43b2-b583-3fc41f5e70fa",
          "name": "getconsolescreenshot",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleScreenshot?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a JPG-format screenshot of a running instance to help with troubleshooting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d50b4f0f-6372-40af-9bb7-0ce67f2e1fe4"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "3c612060-57b4-48fe-9c9e-e767f9dc10ca",
          "name": "getpass