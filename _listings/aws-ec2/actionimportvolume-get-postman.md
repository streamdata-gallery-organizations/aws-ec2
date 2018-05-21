{
  "info": {
    "name": "AWS EC2 API Import Volume",
    "_postman_id": "98ae6d60-0c20-415f-b876-0d2d25fec40a",
    "description": "Creates an import volume task using metadata from the specified disk image.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "a1856696-6ce2-4eff-ad3b-45e837043ca2",
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
              "id": "1d3a0cc4-3546-4a12-974f-1d7ba60de501"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "cc112449-68b3-4280-96a1-4804434483da",
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
              "id": "c68e5262-e7bb-41e0-8846-13fa0a3a7f3e"
            }
          ]
        },
        {
          "id": "722b1412-c32a-4242-aa3d-ea0bbcc1bb73",
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
              "id": "cbe7f828-da71-4b96-b9f3-44179f582c91"
            }
          ]
        },
        {
          "id": "be0fd03c-d648-4add-b90a-c82f613a3c75",
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
              "id": "d03e48f3-db98-45ec-8658-6eec34f16684"
            }
          ]
        },
        {
          "id": "14a3a5e5-0c15-4c77-868e-8e25b03e31fb",
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
              "id": "c3e1b97a-8905-455a-a445-2aef9f0a9eb4"
            }
          ]
        },
        {
          "id": "1ef968dd-dc6b-4937-993a-5451ad2990cb",
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
              "id": "33a09a2a-b753-4e47-b2eb-324dd56a5106"
            }
          ]
        },
        {
          "id": "74cd0df5-3c48-4b5a-a273-92df452917b1",
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
              "id": "429d7080-a080-4c46-9da8-22f240f37c50"
            }
          ]
        },
        {
          "id": "d9a624d7-a085-4da5-91d5-7c53737788d7",
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
              "id": "60ba380e-8529-494f-b725-eae98cbcfcab"
            }
          ]
        },
        {
          "id": "44c2cd41-4068-4fb3-85b3-055769d83d5c",
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
              "id": "7dec235a-b79d-4f82-9b95-017cc841ac49"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "7ba3a01f-52be-4ef7-8f06-d5074bb9c346",
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
              "id": "1877c158-361c-4740-8da9-12f9b53b0421"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "cba1414e-b297-405b-9421-1a7794829b54",
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
              "id": "02dfc94e-1629-4a31-81b8-8084800d241e"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "a4e30e7f-8b38-4830-b87a-d2ff1f77967c",
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
              "id": "a5971c02-65cf-444f-bce6-3fc2b6835e24"
            }
          ]
        },
        {
          "id": "2d374aca-529a-49e2-8a4f-d4575a141375",
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
              "id": "c3f81ac0-99c1-45da-b4b7-5fc9fe2ee7b1"
            }
          ]
        },
        {
          "id": "33be3c93-339e-4c5a-9267-47d58ddc7ebb",
          "name": "cancelconversiontask",
          "request": {
            "url": "http://example.com/api/?Action=CancelConversionTask",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an active conversion task."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6303b606-0a2a-406a-8629-ce3ed9635007"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "e7e3cc9c-ea61-4199-963d-38e3e7415adc",
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
              "id": "5ad97470-49da-43a3-bdd5-73a4b08d11ad"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "a6918062-7c08-4e88-b4bb-bd6e5120e935",
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
              "id": "d08119d5-f585-4857-b0f3-2f205ba55a4e"
            }
          ]
        },
        {
          "id": "fd6e2fb2-4609-4f7a-bc7b-41aeb54250d2",
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
              "id": "30b9f91f-2f27-48b8-a357-f1bf4baf5f31"
            }
          ]
        },
        {
          "id": "92d04546-1d88-4064-9e80-8f37c701a55f",
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
              "id": "f7f34df8-8532-42a1-8ba7-b0a11730cea8"
            }
          ]
        },
        {
          "id": "0f7abf90-4ac3-4b22-afa4-2471916c67b0",
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
              "id": "6da220d0-1eb2-439d-b3a1-04ede28aacbd"
            }
          ]
        },
        {
          "id": "cb3d01ff-c0ce-41c6-96e0-fda2218d6006",
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
              "id": "2c94235c-a4b6-4fe8-9b0d-8ba3d36d5571"
            }
          ]
        },
        {
          "id": "10323bf2-ceac-47f2-be68-e2ec45e8123d",
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
              "id": "944e3174-edce-489b-9965-503a9024f94e"
            }
          ]
        },
        {
          "id": "aa13764d-c345-42df-9c08-49950bb49861",
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
              "id": "14d80900-2eb7-4881-a7be-76ed26efaf04"
            }
          ]
        },
        {
          "id": "767320bf-3f74-430e-a639-3ec706e45df0",
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
              "id": "36700505-d4d9-4e10-9478-4293819f8548"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "f5c19d8a-29b2-4dbd-837c-98e66bad39c0",
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
              "id": "c4e05b63-60d8-4e95-9674-7c5c93ebdf6f"
            }
          ]
        },
        {
          "id": "94b51d7a-f7cf-41d4-86ee-5919a67d434d",
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
              "id": "4965d337-91c0-4b4e-bdc0-fa6af1d325d9"
            }
          ]
        },
        {
          "id": "c37d6ad2-fcdf-4521-ad69-9fddb92dce34",
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
              "id": "bd4050bc-515c-4448-8496-6189787b9d08"
            }
          ]
        },
        {
          "id": "387197f4-efef-47d5-904b-a05d595b4924",
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
              "id": "a70e182a-e44f-4190-92ed-1b1f02b1a380"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "57e054db-2d14-42c5-a3f0-9ac22f9d32d9",
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
              "id": "0e7fb31f-03ce-4545-9b5d-290b1bee9807"
            }
          ]
        },
        {
          "id": "aa690ca2-9f70-4128-85f8-1d3fed67a53e",
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
              "id": "cb88786a-69a2-4744-818f-5fc41a31b5ed"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "bed020f9-2ddd-4a54-860d-7525479d530c",
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
              "id": "182605cb-2b77-4d7b-9777-f07ad36b255d"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "b08d3572-9030-4bfd-b0b4-301588a26d85",
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
              "id": "fd5b712b-161b-4c3d-9604-65ebef5d9f5f"
            }
          ]
        },
        {
          "id": "e179eaa8-c6a3-4c8d-9db5-3b10a258872e",
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
              "id": "d13199be-ba95-4fcd-8622-8c232443a09e"
            }
          ]
        },
        {
          "id": "44e13284-bb18-452b-95e2-1937cedb5362",
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
              "id": "2c1aa8fc-1672-462d-a1e8-a6077ad325a5"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "cbb4d024-94c5-4dab-bfa0-180c2a7b5aab",
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
              "id": "66dbd464-ebb4-4ed5-804b-8155172ba420"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "c253647b-f094-4064-9140-06ae9bc533ef",
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
              "id": "d0435fdd-a1bd-4692-a893-67bf8e7eb59b"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "6859497d-3bb4-475c-a149-bdf30905eff8",
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
              "id": "1606d814-6b6a-4c55-97d3-d63dbd7b3f68"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "024ff510-dfe2-4032-9168-76271e54da18",
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
              "id": "b0d93823-7789-44d4-8cef-0174c0123fc4"
            }
          ]
        },
        {
          "id": "c99f73b4-3999-46f0-8cb9-36e6430f7448",
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
              "id": "4d4f7828-b0f9-4f9d-b536-3b84e7550803"
            }
          ]
        },
        {
          "id": "fbc09b76-fec2-4a67-9f0f-bd2461d367c1",
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
              "id": "eb6e5146-2df0-49de-8430-f6b573aa2bd1"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "9125090c-7df2-4b43-8487-8a671a371beb",
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
              "id": "a78dddef-2b45-49fc-ba7c-b62256da81bd"
            }
          ]
        },
        {
          "id": "043091bd-021a-45bd-a6f6-37e42344d383",
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
              "id": "0b80537d-cd62-4f5d-b327-6b521aecfc2d"
            }
          ]
        },
        {
          "id": "93745204-e3ef-469b-bb0f-973b386c7af0",
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
              "id": "d6809aed-9c7b-464a-b24a-05e2121fb4a8"
            }
          ]
        },
        {
          "id": "35ba7282-a51f-4e16-8026-a9bfc531a277",
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
              "id": "76ee5e01-1b89-43a3-84db-8b948cce639e"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "d3244013-532a-4027-85ef-6fa9fc8b63d9",
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
              "id": "867215cd-c0f4-4a02-8248-df72eca30186"
            }
          ]
        },
        {
          "id": "20605b3f-7b8f-4c4b-bb9f-38df809098d7",
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
              "id": "86b6997c-dbce-4a47-9e97-8c328742bea8"
            }
          ]
        },
        {
          "id": "8e604d50-7b5e-422b-920e-7bb8076c052e",
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
              "id": "e0224823-ed25-4917-9d0a-9068ed39ef86"
            }
          ]
        },
        {
          "id": "28e88e6a-0802-4d8d-b3a2-4015f3955177",
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
              "id": "5213d0fb-b30f-4377-ac74-addf20aa72e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "0f760417-4fae-46ee-8d5b-89b3e30e7507",
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
              "id": "e2471b19-e61d-44e3-b8aa-60b85c3c99bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "460e9858-57ef-4293-be1a-d930c29c112e",
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
              "id": "aa2ae0e7-8cfd-42f5-b060-5f572f71d0b8"
            }
          ]
        },
        {
          "id": "99a46dd4-1d89-4377-b997-1616f0f25392",
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
              "id": "50409f20-3c93-4990-8463-22dae8f80b51"
            }
          ]
        },
        {
          "id": "32d86c7f-f296-4ecd-90c6-a196aed35032",
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
              "id": "dba2bf4a-f066-4656-b019-67fd18949616"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "cb1cf248-786d-4a9c-93b0-dd7018c62e81",
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
              "id": "572dc772-729a-40be-9f2e-25d5f48ed0f3"
            }
          ]
        },
        {
          "id": "dec1b2f2-d9f2-486b-9089-b8ff5521ccd6",
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
              "id": "1681af59-0971-497e-9646-ccfd27beeb72"
            }
          ]
        },
        {
          "id": "91f24428-0487-4dc1-a5ff-781c10aa0f1e",
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
              "id": "c4c2b978-b42a-4ddd-8798-4e951187b46f"
            }
          ]
        },
        {
          "id": "3b01ec93-eecc-4fda-954e-4623df95b043",
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
              "id": "8e341ca6-e13d-45cf-82ab-d25e9d083c7a"
            }
          ]
        },
        {
          "id": "74aa7f14-5d61-4b46-9c18-5615ff7e8ff4",
          "name": "importsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=ImportSnapshot?AvailabilityZone=AvailabilityZone&Description=Description&DryRun=DryRun&Image=Image&Volume=Volume",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your import snapshot tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27534eef-d507-4a63-b5b5-efb586111520"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "e1f4b642-90a6-4971-88e4-25677cc18fe7",
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
              "id": "51325017-ce04-446f-a7a0-5065918cda40"
            }
          ]
        },
        {
          "id": "1a21ced9-e11a-402a-8646-7aadcb1fc5f8",
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
              "id": "fe8a6fb6-9f08-458a-8593-0fc4c8497f6e"
            }
          ]
        },
        {
          "id": "979c9fd7-1378-42ea-9b75-55f7771a03ca",
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
              "id": "3404df4b-562a-4838-bc47-af8767fddae6"
            }
          ]
        },
        {
          "id": "87db653c-5282-4063-952f-ad33a0772925",
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
              "id": "c3685ff0-440d-458d-8973-c26b3d7ea43b"
            }
          ]
        },
        {
          "id": "b5abb6c8-5cda-4db6-b58b-1fd6ca0e4b34",
          "name": "importvolume",
          "request": {
            "url": "http://example.com/api/?Action=ImportVolume?ExportTaskId=ExportTaskId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an import volume task using metadata from the specified disk image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7ebb3cb-f51d-491d-b83a-cf195309eed7"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "a07dea33-feba-479c-a5ca-725af0cdf775",
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
              "id": "c7ecacec-4b7b-480c-93e9-c7ebc5086318"
            }
          ]
        },
        {
          "id": "a22d5135-efe2-4802-8489-31b30e2759ee",
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
              "id": "a091d3d8-dcf1-4a78-8c75-d6df2260b10a"
            }
          ]
        },
        {
          "id": "39896473-f42c-4802-82d5-79078bbb9046",
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
              "id": "178dc22e-1848-4f04-b7fd-6898a8111f62"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "38dcc959-88b0-474d-b5d4-0a2a1ae227fd",
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
              "id": "1dc3624b-5804-4d65-8285-48dce05f213b"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "4f561844-9dc3-469c-b613-ec0ac2a16176",
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
              "id": "946c8444-5320-4348-8fbb-f3a8709871ac"
            }
          ]
        },
        {
          "id": "a1a39dec-849d-4b20-86af-6255d0bc3ce7",
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
              "id": "f9640fe4-2d6e-4cb0-a309-278026830f0c"
            }
          ]
        },
        {
          "id": "fedcd79a-3519-4163-aea7-92634e7e21a4",
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
              "id": "07ac8b57-8341-4b69-af42-e390fcb448e3"
            }
          ]
        },
        {
          "id": "3fe8239a-2034-4a6f-8c2c-ee243ddd9364",
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
              "id": "7a966c70-89ad-4d8b-b67f-303a2af4ae05"
            }
          ]
        },
        {
          "id": "43bbd714-930e-4e66-a530-b66ff54d1c5b",
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
              "id": "d5e295cd-ed80-4325-9a9b-82e8fe8ae4f3"
            }
          ]
        },
        {
          "id": "cca0cd49-1d26-4939-bcfb-c6c5471a35b2",
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
              "id": "7b0e7119-1f9c-4ffe-b94c-316a9051820a"
            }
          ]
        },
        {
          "id": "70114feb-7cc2-4e0e-b3b0-c15c7470de11",
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
              "id": "229904fb-5668-4907-a095-f7d56e17217f"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "3e6f068c-2657-45e5-9ab0-eb709b3f32ca",
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
              "id": "5c1bd9e6-b80e-4efb-b0de-098132573ab7"
            }
          ]
        },
        {
          "id": "a475f25e-6e06-484b-a924-1989625f15f1",
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
              "id": "4c0785cb-416d-409f-84b2-57b8299cccb8"
            }
          ]
        },
        {
          "id": "c5a519da-5dfe-4003-bc1d-a6275a968bb6",
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
              "id": "14ee43a0-0343-427f-a6a8-4d4ab955a2eb"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "ebd19297-74a2-4f1e-a41d-8b999c22c1ff",
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
              "id": "9321a0a0-c5fe-4210-8268-180b4645c2bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "9c5946bd-7723-4655-8d5b-66e8820d272d",
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
              "id": "c0a4e188-4538-42e4-902e-9c34b11571f6"
            }
          ]
        },
        {
          "id": "1cf2467c-ce62-46f6-9f6c-569140c1ccf3",
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
              "id": "0714e861-fec0-4d38-9baa-c89c348aebc1"
            }
          ]
        },
        {
          "id": "e4047e83-73de-431f-882c-f0a9953efd9e",
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
              "id": "4be00bd2-5d1c-40e8-badb-975db9371fa9"
            }
          ]
        },
        {
          "id": "a94dd947-5a81-4be1-83a4-aa52077a1c48",
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
              "id": "a2914d84-3955-45bc-96ef-252e88cd1c91"
            }
          ]
        },
        {
          "id": "91c96d61-3b9c-4ad9-8e71-8c9b56f973a5",
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
              "id": "30c11806-830d-4afc-bdf5-4288bf6bafd9"
            }
          ]
        },
        {
          "id": "37652920-6236-497d-8c61-697dc70db31e",
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
              "id": "76fdefee-dd9c-44f2-b88b-0234ef2ed0db"
            }
          ]
        },
        {
          "id": "80d66a43-d99d-4191-93d6-96fb8da8d4ef",
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
              "id": "1324ab66-257c-4532-8c4e-2fc5a71864e4"
            }
          ]
        },
        {
          "id": "a1371c0b-0701-475f-86aa-ca521e2bfb74",
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
              "id": "71212e4f-5455-4b6a-8eec-ff15ef0ef512"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "36a66cbc-c5fa-4241-92e2-12f884f54404",
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
              "id": "1a1176f1-e261-4ad3-a352-52e2c4760f28"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "1f8849a2-3cb7-499e-af69-f226cf38949b",
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
              "id": "91a3788b-3c6b-45f9-a03e-d419cda2bad9"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "df51c857-8230-4d68-b84e-abd4474b6529",
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
              "id": "8f799510-403f-49bb-8bd5-4da127138b47"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "e213b094-13fd-470b-afd2-2fa2061cbb42",
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
              "id": "248b6692-89c0-4fa0-9328-12479e5593aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "5d927d25-93f4-45c6-a352-af6e6a585415",
          "name": "getpassworddata",
          "request": {
            "url": "http://example.com/api/?Action=GetPasswordData?Attribute=Attribute&BlockDeviceMapping.N=BlockDeviceMapping.N&DisableApiTermination=DisableApiTermination&DryRun=DryRun&EbsOptimized=EbsOptimized&EnaSupport=EnaSupport&GroupId.N=GroupId.N&InstanceId=InstanceId&InstanceInitiatedShutdownBehavior=InstanceInitiatedShutdownBehavior&InstanceType=InstanceType&Kernel=Kernel&Ramdisk=Ramdisk&SourceDestCheck=SourceDestCheck&SriovNetSupport=SriovNetSupport&UserData=UserData&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the encrypted administrator password for an instance running Windows."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eff75f8e-9458-49c1-8bfb-27c4c0806831"
            }
          ]
        }
      ]
    },
    {
      "name": "Monitor Instance",
      "item": [
        {
          "id": "f2b83874-525b-4a9e-92b9-fea17db89e6a",
          "name": "monitorinstances",
          "request": {
            "url": "http://example.com/api/?Action=MonitorInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables detailed monitoring for a running instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15b2b70e-ecb3-4cdb-9ae8-f11989ad97fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance",
      "item": [
        {
          "id": "2f19a75e-1d36-4a03-a971-4ca154d58afd",
          "name": "rebootinstances",
          "request": {
            "url": "http://example.com/api/?Action=RebootInstances?Description=Description&DryRun=DryRun&EndTime=EndTime&InstanceId.N=InstanceId.N&ReasonCode.N=ReasonCode.N&StartTime=StartTime&Status=Status",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a reboot of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "914e7150-0266-4568-9430-0a6372d7866b"
            }
          ]
        },
        {
          "id": "378ddec9-7711-4171-a73e-203108f05b7a",
          "name": "importinstance",
          "request": {
            "url": "http://example.com/api/?Action=ImportInstance",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an import instance task using metadata from the specified disk image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92be65d3-e6c5-4c82-a44e-2c0221642911"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "325bff5b-b460-4ad3-8ae4-a7055eeb2fe1",
          "name": "runinstances",
          "request": {
            "url": "http://example.com/api/?Action=RunInstances?AdditionalInfo=AdditionalInfo&DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Launches the specified number of instances using an AMI for which you have\n            permissions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51625ef3-4077-4bf0-ad67-6aa7478a8158"
            }
          ]
        },
        {
          "id": "3ef526d3-4b4c-4b0e-989c-afac586b0384",
          "name": "startinstances",
          "request": {
            "url": "http://example.com/api/?Action=StartInstances?DryRun=DryRun&Force=Force&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts an Amazon EBS-backed AMI that you've previously stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c71f11f1-66e1-42ee-9aad-c1051e502835"
            }
          ]
        },
        {
          "id": "ea7c7b8f-622c-44e6-b81b-a5013ff3964b",
          "name": "stopinstances",
          "request": {
            "url": "http://example.com/api/?Action=StopInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops an Amazon EBS-backed instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "976ac5d8-6846-46f9-ba65-6ea94d793b60"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminal Instances",
      "item": [
        {
          "id": "9e201c49-8dcb-4f98-a393-15668a467c2d",
          "name": "terminateinstances",
          "request": {
            "url": "http://example.com/api/?Action=TerminateInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Shuts down one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12b966ae-5302-45f9-b29a-cf0bdd1f8bd0"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateway",
      "item": [
        {
          "id": "3317d6c3-fa7a-40d4-8383-081fb284b0eb",
          "name": "attachinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=AttachInternetGateway?ClientToken=ClientToken&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an Internet gateway to a VPC, enabling connectivity between the Internet\n\t\t\t\tand the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cec207b-2588-4691-be49-c859127e6adb"
            }
          ]
        },
        {
          "id": "ceebb3d6-68e6-4b72-821d-afd033a672ec",
          "name": "createegressonlyinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateEgressOnlyInternetGateway?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[IPv6 only] Creates an egress-only Internet gateway for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03980c15-0827-4ad1-b683-6d73a237f964"
            }
          ]
        },
        {
          "id": "ba713e85-83bd-4359-ae1e-7f6960d1697f",
          "name": "createinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateInternetGateway?DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Internet gateway for use with a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93857568-926a-4e9c-a9d7-eb6f62ac5cb9"
            }
          ]
        },
        {
          "id": "6e5d54ef-4f2d-453a-a7f1-ba3c9e987d82",
          "name": "deleteegressonlyinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEgressOnlyInternetGateway?DryRun=DryRun&InternetGatewayId=InternetGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an egress-only Internet gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b2fd850-1d5f-4592-9169-0758bd0273a0"
            }
          ]
        },
        {
          "id": "c1bc719b-e80c-4b2f-afdf-5f0aa4ad4c64",
          "name": "deleteinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInternetGateway?DryRun=DryRun&EgressOnlyInternetGatewayId.N=EgressOnlyInternetGatewayId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Internet gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "210cc3eb-65fb-41eb-86c6-badd5a30c5d8"
            }
          ]
        },
        {
          "id": "ffdfc448-6e24-4944-b186-b77c4f4e1d7f",
          "name": "describeegressonlyinternetgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEgressOnlyInternetGateways?DryRun=DryRun&Filter.N=Filter.N&InternetGatewayId.N=InternetGatewayId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your egress-only Internet gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90beb07c-7e0c-499e-bf3f-18e5b90fd65e"
            }
          ]
        },
        {
          "id": "e32f6f96-f88d-4886-8433-1eba4b96d8d8",
          "name": "detachinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DetachInternetGateway?DryRun=DryRun&KeyName=KeyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an Internet gateway from a VPC, disabling connectivity between the Internet and the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b634c4d-b6e4-41a3-b861-a999062126be"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateways",
      "item": [
        {
          "id": "d03c5bcd-9baa-46e1-9887-6f73fc6eed7d",
          "name": "describeinternetgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInternetGateways?DryRun=DryRun&InternetGatewayId=InternetGatewayId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Internet gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeb511bf-0b7a-431d-9592-a44580dabdcc"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pair",
      "item": [
        {
          "id": "cec894e5-beae-46a9-a495-d52294e9d8b3",
          "name": "createkeypair",
          "request": {
            "url": "http://example.com/api/?Action=CreateKeyPair?DryRun=DryRun&KeyName=KeyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a 2048-bit RSA key pair with the specified name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3eb1f25e-32de-45ce-9b4b-55451d9a2655"
            }
          ]
        },
        {
          "id": "20001c39-2ab8-4c3f-8eb2-724b13bb1542",
          "name": "deletekeypair",
          "request": {
            "url": "http://example.com/api/?Action=DeleteKeyPair?DryRun=DryRun&Filter.N=Filter.N&KeyName.N=KeyName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified key pair, by removing the public key from Amazon EC2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb7e5e2b-16b9-455e-8962-fba34520efc9"
            }
          ]
        },
        {
          "id": "7d469af3-31da-4f01-b934-5c5699f61ed2",
          "name": "importkeypair",
          "request": {
            "url": "http://example.com/api/?Action=ImportKeyPair?AllocationId=AllocationId&ClientToken=ClientToken&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Imports the public key from an RSA key pair that you created with a third-party tool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c369eb5b-8ff1-405b-a0ac-890ca526ffd2"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Paris",
      "item": [
        {
          "id": "e5496bc6-01b1-4c13-b419-2ffbe5fc3772",
          "name": "describekeypairs",
          "request": {
            "url": "http://example.com/api/?Action=DescribeKeyPairs?DryRun=DryRun&KeyName=KeyName&PublicKeyMaterial=PublicKeyMaterial",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your key pairs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "004d3c1c-5fc7-4058-891e-b277fddcfa3f"
            }
          ]
        }
      ]
    },
    {
      "name": "NAT Gateways",
      "item": [
        {
          "id": "560c60f9-98d2-40bb-bf90-cca746fbac6c",
          "name": "describenatgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNatGateways?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the your NAT gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b35d5cb-1293-4cda-881d-36214c48453c"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC ACL",
      "item": [
        {
          "id": "221128d9-a7bb-4496-bc6f-78aff4fcd2b1",
          "name": "createnetworkacl",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkAcl?CidrBlock=CidrBlock&DryRun=DryRun&Egress=Egress&Icmp=Icmp&Ipv6CidrBlock=Ipv6CidrBlock&NetworkAclId=NetworkAclId&PortRange=PortRange&Protocol=Protocol&RuleAction=RuleAction&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network ACL in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca8a27da-eb39-4202-bb80-b7791c0b0f96"
            }
          ]
        },
        {
          "id": "33a52acd-15dd-4a6b-903f-fa302505f563",
          "name": "createnetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkAclEntry?DryRun=DryRun&NetworkAclId=NetworkAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an entry (a rule) in a network ACL with the specified rule number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9adc9959-1d21-4f70-aa93-c8107408af63"
            }
          ]
        }
      ]
    },
    {
      "name": "Network ACL",
      "item": [
        {
          "id": "3b2f21a8-f210-4044-b1d6-fb83b99686de",
          "name": "deletenetworkacl",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkAcl?DryRun=DryRun&Egress=Egress&NetworkAclId=NetworkAclId&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d1fdccd-60a5-411a-908d-ea12422cbf62"
            }
          ]
        },
        {
          "id": "0d55048b-c25b-4cd5-92c5-ee03038ba699",
          "name": "deletenetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkAclEntry?DryRun=DryRun&Filter.N=Filter.N&NetworkAclId.N=NetworkAclId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified ingress or egress entry (rule) from the specified network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b540295-e3c6-4336-861b-a3d88c41ceaf"
            }
          ]
        },
        {
          "id": "b3e84e28-123e-4f4b-b4e9-dd9e1a129167",
          "name": "describenetworkacls",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkAcls?AssociationId=AssociationId&DryRun=DryRun&NetworkAclId=NetworkAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network ACLs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8bbadcaa-8f44-457d-82f1-a6f6c66fdcef"
            }
          ]
        },
        {
          "id": "15ea492c-f2e2-4645-901e-28d0bd7f7b2c",
          "name": "replacenetworkaclassociation",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceNetworkAclAssociation?CidrBlock=CidrBlock&DryRun=DryRun&Egress=Egress&Icmp=Icmp&Ipv6CidrBlock=Ipv6CidrBlock&NetworkAclId=NetworkAclId&PortRange=PortRange&Protocol=Protocol&RuleAction=RuleAction&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes which network ACL a subnet is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d32817b1-e5b8-4f12-89f5-0648039bca9b"
            }
          ]
        },
        {
          "id": "20b600d8-f12e-44c8-a01f-9b432f9af4cd",
          "name": "replacenetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceNetworkAclEntry?DryRun=DryRun&GroupName=GroupName&Strategy=Strategy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Replaces an entry (rule) in a network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ed904be-1cbd-4dec-9a8a-f8dab4e40dc7"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Group",
      "item": [
        {
          "id": "3780ef2e-ad72-4610-9ac1-a9c891b108fb",
          "name": "createplacementgroup",
          "request": {
            "url": "http://example.com/api/?Action=CreatePlacementGroup?DryRun=DryRun&GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a placement group that you launch cluster instances into."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c45f95e-bd8f-4f8e-a411-ad4d11659341"
            }
          ]
        },
        {
          "id": "a5019eae-e08e-4b10-a25f-210bddc74c32",
          "name": "deleteplacementgroup",
          "request": {
            "url": "http://example.com/api/?Action=DeletePlacementGroup?DryRun=DryRun&Filter.N=Filter.N&GroupName.N=GroupName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified placement group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa69bb4b-7256-4749-8128-6a5161d37c07"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Groups",
      "item": [
        {
          "id": "78344ae2-8fdc-4710-85d6-fc6ce527a11a",
          "name": "describeplacementgroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribePlacementGroups?DryRun=DryRun&Filter.N=Filter.N&ZoneName.N=ZoneName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your placement groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8980e39-a882-4363-8745-79677fb48746"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Zones",
      "item": [
        {
          "id": "d6ee5e48-c48c-4509-9cc7-7ef14b93da15",
          "name": "describeavailabilityzones",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAvailabilityZones?DryRun=DryRun&Filter.N=Filter.N&RegionName.N=RegionName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the Availability Zones that are available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68907efb-32b8-4cd6-bd49-000b9e3f8115"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "57a794ef-dfa2-4eb5-b2b2-4592ce3718c9",
          "name": "describeregions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRegions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more regions that are currently available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed56f7df-76c3-4874-afaa-044b3cddce00"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instances",
      "item": [
        {
          "id": "10229823-d0cf-40b7-b099-26ad5e8ff83b",
          "name": "acceptreservedinstancesexchangequote",
          "request": {
            "url": "http://example.com/api/?Action=AcceptReservedInstancesExchangeQuote?ReservedInstancesListingId=ReservedInstancesListingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts the Convertible Reserved Instance exchange quote described in the GetReservedInstancesExchangeQuote call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18e26047-e61b-425f-8560-13539114bbee"
            }
          ]
        },
        {
          "id": "1746b17f-2d77-451a-bfe1-25e4528fbbcc",
          "name": "describereservedinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstances?Filter.N=Filter.N&ReservedInstancesId=ReservedInstancesId&ReservedInstancesListingId=ReservedInstancesListingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the Reserved Instances that you purchased."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2adaf6a7-1eb4-40ad-a2ac-fd55b0b0e720"
            }
          ]
        },
        {
          "id": "46c3593b-232b-43fa-84cd-64d02808a390",
          "name": "describereservedinstanceslistings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesListings?Filter.N=Filter.N&NextToken=NextToken&ReservedInstancesModificationId.N=ReservedInstancesModificationId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your account's Reserved Instance listings in the Reserved Instance Marketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3df80f9-c9fb-4917-895a-a90e9c69a3dd"
            }
          ]
        },
        {
          "id": "76ebd6f2-2eff-4c7f-84c4-754db8e55cb2",
          "name": "describereservedinstancesmodifications",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesModifications?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Filter.N=Filter.N&IncludeMarketplace=IncludeMarketplace&InstanceTenancy=InstanceTenancy&InstanceType=InstanceType&MaxDuration=MaxDuration&MaxInstanceCount=MaxInstanceCount&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingClass=OfferingClass&OfferingType=OfferingType&ProductDescription=ProductDescription&ReservedInstancesOfferingId.N=ReservedInstancesOfferingId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the modifications made to your Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7121c737-6118-40a3-ac41-68f7c1f3b24e"
            }
          ]
        },
        {
          "id": "a7df6412-7713-4a8d-b542-8c57d9adafaf",
          "name": "describereservedinstancesofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesOfferings?DryRun=DryRun&ReservedInstanceId.N=ReservedInstanceId.N&TargetConfiguration.N=TargetConfiguration.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Reserved Instance offerings that are available for purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f412c797-b30a-4cd7-9a38-78cb0e358fd0"
            }
          ]
        },
        {
          "id": "48c201f7-a101-4d65-b437-14fc5e9589a6",
          "name": "getreservedinstancesexchangequote",
          "request": {
            "url": "http://example.com/api/?Action=GetReservedInstancesExchangeQuote?ClientToken=ClientToken&ReservedInstancesConfigurationSetItemType.N=ReservedInstancesConfigurationSetItemType.N&ReservedInstancesId.N=ReservedInstancesId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns details about the values and term of your specified Convertible Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99f915b2-5ed7-44e9-8d5c-a178b4714aef"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instance",
      "item": [
        {
          "id": "797fdd59-ecdb-4ddc-b079-b8adf064014e",
          "name": "cancelreservedinstanceslisting",
          "request": {
            "url": "http://example.com/api/?Action=CancelReservedInstancesListing?ClientToken=ClientToken&InstanceCount=InstanceCount&PriceSchedules.N=PriceSchedules.N&ReservedInstancesId=ReservedInstancesId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the specified Reserved Instance listing in the Reserved Instance Marketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a16f21b-f7bc-4484-9947-0aaeb5b0457a"
            }
          ]
        },
        {
          "id": "fce58998-5c4b-4376-bf70-b6702eceb3b8",
          "name": "createreservedinstanceslisting",
          "request": {
            "url": "http://example.com/api/?Action=CreateReservedInstancesListing?DryRun=DryRun&Filter.N=Filter.N&OfferingClass=OfferingClass&OfferingType=OfferingType&ReservedInstancesId.N=ReservedInstancesId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a listing for Amazon EC2 Standard Reserved Instances to be sold in the Reserved Instance\n\t\t\tMarketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36213db1-e12d-4121-a365-b8fe555cb2d6"
            }
          ]
        },
        {
          "id": "759bedd1-5e9f-4867-8b7d-640c0a128c3c",
          "name": "modifyreservedinstances",
          "request": {
            "url": "http://example.com/api/?Action=ModifyReservedInstances?DryRun=DryRun&InstanceCount=InstanceCount&LimitPrice=LimitPrice&ReservedInstancesOfferingId=ReservedInstancesOfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the Availability Zone, instance count, instance type, or network platform (EC2-Classic or EC2-VPC) of your Standard Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3fc52dfe-d7f7-429b-909b-5bcb1066215a"
            }
          ]
        },
        {
          "id": "6accddfe-5e8a-42b4-adda-20847654dd8f",
          "name": "purchasereservedinstancesoffering",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseReservedInstancesOffering?PrincipalArn=PrincipalArn&Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchases a Reserved Instance for use with your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8281e8d-9bbd-4062-9864-bf14b240ddc7"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Format",
      "item": [
        {
          "id": "cdcb17ea-6d2c-4345-89b2-a9051731e34d",
          "name": "describeidentityidformat",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentityIdFormat?Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ID format settings for resources for the specified IAM user, IAM role, or root\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c74abbf7-1083-431a-940a-43f7cfc3d002"
            }
          ]
        },
        {
          "id": "3e1de37c-8e3f-4c58-8ce5-0d837b65c234",
          "name": "describeidformat",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdFormat?PrincipalArn=PrincipalArn&Resource=Resource&UseLongIds=UseLongIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ID format settings for your resources on a per-region basis, for example, to view which resource types are enabled for longer IDs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86e5b78f-ea3c-471e-b734-097cb4dbf4c3"
            }
          ]
        },
        {
          "id": "caab17df-0089-46df-9bfe-d29f04e35635",
          "name": "modifyidentityidformat",
          "request": {
            "url": "http://example.com/api/?Action=ModifyIdentityIdFormat?Resource=Resource&UseLongIds=UseLongIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the ID format of a resource for a specified IAM user, IAM role, or the root\n      user for an account; or all IAM users, IAM roles, and the root user for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "864793a0-41a6-4313-80c3-852dc8f844a0"
            }
          ]
        },
        {
          "id": "b90152c3-fcb9-4ec8-ae47-0b94328610d7",
          "name": "modifyidformat",
          "request": {
            "url": "http://example.com/api/?Action=ModifyIdFormat?DryRun=DryRun&RouteTableId=RouteTableId&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the ID format for the specified resource on a per-region basis."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "100fccd8-414a-48fe-9a4a-acc47610106b"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Table",
      "item": [
        {
          "id": "74429b49-6c61-4926-b7dd-12d59728b30d",
          "name": "associateroutetable",
          "request": {
            "url": "http://example.com/api/?Action=AssociateRouteTable?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId&GatewayId=GatewayId&InstanceId=InstanceId&NatGatewayId=NatGatewayId&NetworkInterfaceId=NetworkInterfaceId&RouteTableId=RouteTableId&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a subnet with a route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f279161-a2e4-4caa-90b4-8efb7df94c39"
            }
          ]
        },
        {
          "id": "b250f20b-7245-4de3-8466-00b222524105",
          "name": "createroute",
          "request": {
            "url": "http://example.com/api/?Action=CreateRoute?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a route in a route table within a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "382464b5-6a0a-4d81-b56f-9d8652e2efc4"
            }
          ]
        },
        {
          "id": "967b078e-5e9f-4d87-83a5-3a0a2e6cafab",
          "name": "createroutetable",
          "request": {
            "url": "http://example.com/api/?Action=CreateRouteTable?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a route table for the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c40be225-be9d-48c9-a890-371728bf447b"
            }
          ]
        },
        {
          "id": "a2e9541f-cf69-451e-b6f3-6d4a48d68ed2",
          "name": "deleteroutetable",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRouteTable?DryRun=DryRun&Filter.N=Filter.N&RouteTableId.N=RouteTableId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5561d68e-3b66-4825-8861-0caeb14e0bf8"
            }
          ]
        },
        {
          "id": "5f8d4408-32e7-4a54-9305-5a636f49dcca",
          "name": "disassociateroutetable",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateRouteTable?GatewayId=GatewayId&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a subnet from a route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00dc6def-a15a-4b97-b1ee-a68cb5f440d7"
            }
          ]
        },
        {
          "id": "8ef82ac0-fe03-491d-bc19-1e11c5e0583c",
          "name": "replaceroutetableassociation",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceRouteTableAssociation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the route table associated with a given subnet in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0ccd6a3-0884-40c7-b87f-33a6a9bcbd71"
            }
          ]
        }
      ]
    },
    {
      "name": "Route",
      "item": [
        {
          "id": "43a8a94a-cf2b-41a7-b4df-fc056aa94b27",
          "name": "deleteroute",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRoute?DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified route from the specified route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "713f211b-40c0-4c5d-8f35-1bbf826e2a3a"
            }
          ]
        },
        {
          "id": "186dbefb-4b02-43ad-94a1-b9e997650fdd",
          "name": "replaceroute",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceRoute?AssociationId=AssociationId&DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Replaces an existing route within a route table in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "deb74a79-210a-4beb-95e4-1cdf8a537279"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "3b2411de-a7b2-4d0f-8fa7-b24732bc0b3e",
          "name": "describeroutetables",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRouteTables?GatewayId=GatewayId&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your route tables."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0b2c811-ad45-4725-8934-5b3604587dc1"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway",
      "item": [
        {
          "id": "9677a51f-1ec3-4818-9986-1394ef9ede02",
          "name": "disablevgwroutepropagation",
          "request": {
            "url": "http://example.com/api/?Action=DisableVgwRoutePropagation?AssociationId=AssociationId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables a virtual private gateway (VGW) from propagating routes to a specified route table of a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd8a0cbc-c71e-4420-ac2f-5bc1563a66f0"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway Route Propogation",
      "item": [
        {
          "id": "2443b6a6-9591-4caf-8fb6-7126bb4c1abc",
          "name": "enablevgwroutepropagation",
          "request": {
            "url": "http://example.com/api/?Action=EnableVgwRoutePropagation?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId&GatewayId=GatewayId&InstanceId=InstanceId&NatGatewayId=NatGatewayId&NetworkInterfaceId=NetworkInterfaceId&RouteTableId=RouteTableId&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a virtual private gateway (VGW) to propagate routes to the specified route table of a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3ba0efa-660b-488c-a2fa-9dd04cadb03a"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Availability",
      "item": [
        {
          "id": "3934c4fb-a3c7-4356-98ae-6c359e9413ba",
          "name": "describescheduledinstanceavailability",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScheduledInstanceAvailability",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Finds available schedules that meet the specified criteria."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf25846d-7920-4418-b99b-e46482de29e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Server Instances",
      "item": [
        {
          "id": "00096654-976f-40e6-a04e-ebbe2824fc19",
          "name": "describescheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScheduledInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Scheduled Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "766ff810-aa56-4090-b201-28af82bdad5b"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instance",
      "item": [
        {
          "id": "8f2d9d09-a5f9-46d2-acac-f57dd68c261b",
          "name": "purchasescheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseScheduledInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchases one or more Scheduled Instances with the specified schedule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36015f30-46ad-40fb-aebc-db6aca09cfe7"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instances",
      "item": [
        {
          "id": "d7941bf4-91de-487a-b430-f735c366c6a3",
          "name": "runscheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=RunScheduledInstances?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Launches the specified Scheduled Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc0c2e51-7b72-4c43-a7c7-b383b8266bbb"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Group",
      "item": [
        {
          "id": "bb05a7d1-1b85-419d-9fcf-20e38996ccc3",
          "name": "authorizesecuritygroupegress-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=AuthorizeSecurityGroupEgress (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&GroupName=GroupName&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Adds one or more egress rules to a security group for use with a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c23af842-452b-4889-82ab-5f09c6998c59"
            }
          ]
        },
        {
          "id": "6f76d656-0703-46e8-9ff8-6750878d42a6",
          "name": "authorizesecuritygroupingress",
          "request": {
            "url": "http://example.com/api/?Action=AuthorizeSecurityGroupIngress?DryRun=DryRun&GroupDescription=GroupDescription&GroupName=GroupName&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds one or more ingress rules to a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3653038-8e0c-489d-b1c1-d7c48b0d05b4"
            }
          ]
        },
        {
          "id": "1ea8d6ab-a19a-40d4-88ee-53380cb1b5bb",
          "name": "createsecuritygroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateSecurityGroup?DryRun=DryRun&GroupId=GroupId&GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09972d5b-339d-48e7-9c17-0bab94acff37"
            }
          ]
        },
        {
          "id": "60ef6a7d-fb65-4a61-b6d8-a1fad78d96dc",
          "name": "describesecuritygroupreferences-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSecurityGroupReferences (EC2-VPC only)?DryRun=DryRun&Filter.N=Filter.N&GroupId.N=GroupId.N&GroupName.N=GroupName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Describes the VPCs on the other side of a VPC peering connection that are referencing the security groups you've specified in this request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12dd7644-764e-4420-ad9d-177a0303c6d0"
            }
          ]
        },
        {
          "id": "f849876e-aac0-4f15-9c8f-d0c467cf4525",
          "name": "describesecuritygroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSecurityGroups?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your security groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e81d9623-67d3-4795-a601-cbf1fec2aba5"
            }
          ]
        }
      ]
    },
    {
      "name": "Security  Group",
      "item": [
        {
          "id": "b237669d-8241-4d18-b32a-8f76422d6475",
          "name": "deletesecuritygroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSecurityGroup?DryRun=DryRun&GroupId.N=GroupId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7243bf08-024c-4ed0-b064-03808e1c7917"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Groups",
      "item": [
        {
          "id": "d8399c14-9c1c-44c6-a00f-04f24aa52bb3",
          "name": "describestalesecuritygroups-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStaleSecurityGroups (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Describes the stale security group rules for security groups in a specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee811d89-8121-403d-b52b-8e15ed3b8c6e"
            }
          ]
        },
        {
          "id": "0c0316e2-f12e-4eca-8981-f79fc52c0d7f",
          "name": "revokesecuritygroupegress-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=RevokeSecurityGroupEgress (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&GroupName=GroupName&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Removes one or more egress rules from a security group for EC2-VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29c6deb4-e463-4473-87c0-824b25cca9ac"
            }
          ]
        },
        {
          "id": "e01e6fda-337d-4a4d-adc3-ed9255b8fb8a",
          "name": "revokesecuritygroupingress",
          "request": {
            "url": "http://example.com/api/?Action=RevokeSecurityGroupIngress?DryRun=DryRun&SpotInstanceRequestId.N=SpotInstanceRequestId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes one or more ingress rules from a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a476b90a-fc02-4628-ae30-d2fc933cc71b"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance",
      "item": [
        {
          "id": "68e3f40e-7cf3-489e-a5b7-2b18aff0e03a",
          "name": "cancelspotinstancerequests",
          "request": {
            "url": "http://example.com/api/?Action=CancelSpotInstanceRequests?Bucket=Bucket&DryRun=DryRun&Prefix=Prefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels one or more Spot instance requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83baa754-67e2-4d3f-b3cc-ed3dc197d46f"
            }
          ]
        },
        {
          "id": "5900a46e-77e5-481b-a179-87e4941e0cff",
          "name": "requestspotinstances",
          "request": {
            "url": "http://example.com/api/?Action=RequestSpotInstances?DryRun=DryRun&SpotFleetRequestId.N=SpotFleetRequestId.N&TerminateInstances=TerminateInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a Spot instance request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c39a649-d776-45b1-adad-3967e8ef0862"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnet",
      "item": [
        {
          "id": "222f5ed5-883c-41d7-bdb3-2f72ed1c945f",
          "name": "createspotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=CreateSpotDatafeedSubscription?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a data feed for Spot instances, enabling you to view Spot instance usage logs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc2a5f74-9baf-43ba-be99-2d04e61f527f"
            }
          ]
        },
        {
          "id": "dc267f55-aa7c-44c2-91d7-79e216fde446",
          "name": "createsubnet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSubnet?DryRun=DryRun&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a subnet in an existing VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6e2cb91-e489-4f3b-b429-488adcd3375f"
            }
          ]
        },
        {
          "id": "f75d57ca-5dae-40aa-bcfd-d7f102b607d9",
          "name": "deletesubnet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSubnet?DryRun=DryRun&Filter.N=Filter.N&SubnetId.N=SubnetId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "927bf0c8-f7c4-464b-9acd-415666dea9be"
            }
          ]
        },
        {
          "id": "a0788238-bab7-47b1-91b8-d5987d913af6",
          "name": "modifysubnetattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifySubnetAttribute?DryRun=DryRun&ResourceId.N=ResourceId.N&Tag.N=Tag.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies a subnet attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3976d742-850a-4c48-8479-ee4819b98558"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed Subscription",
      "item": [
        {
          "id": "e7614340-f50a-4328-9cc7-4a3daf5a9006",
          "name": "deletespotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSpotDatafeedSubscription?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the data feed for Spot instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62e406d0-7a81-4651-807f-df5a05ce119b"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed",
      "item": [
        {
          "id": "bc982a0b-159d-45b6-81e8-289c3c1014bb",
          "name": "describespotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotDatafeedSubscription?DryRun=DryRun&Filter.N=Filter.N&SpotInstanceRequestId.N=SpotInstanceRequestId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the data feed for Spot instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cba6b49-e76d-4d20-8ee7-97be5a7ccc45"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "24633f8f-f09d-402a-8ba8-f29a6b40646c",
          "name": "describespotinstancerequests",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotInstanceRequests?AvailabilityZone=AvailabilityZone&DryRun=DryRun&EndTime=EndTime&Filter.N=Filter.N&InstanceType.N=InstanceType.N&MaxResults=MaxResults&NextToken=NextToken&ProductDescription.N=ProductDescription.N&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Spot instance requests that belong to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6994e1b-f723-4994-9dda-7ea22d65fb6b"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Price History",
      "item": [
        {
          "id": "b4a51c10-bf49-4eba-9938-be9bb665771b",
          "name": "describespotpricehistory",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotPriceHistory?AvailabilityZoneGroup=AvailabilityZoneGroup&BlockDurationMinutes=BlockDurationMinutes&ClientToken=ClientToken&DryRun=DryRun&InstanceCount=InstanceCount&LaunchGroup=LaunchGroup&LaunchSpecification=LaunchSpecification&SpotPrice=SpotPrice&Type=Type&ValidFrom=ValidFrom&ValidUntil=ValidUntil",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Spot price history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9bf2f60a-69fc-4af2-8370-b6609046fde1"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet",
      "item": [
        {
          "id": "71e9f36f-b147-4179-a649-48641cd61add",
          "name": "cancelspotfleetrequests",
          "request": {
            "url": "http://example.com/api/?Action=CancelSpotFleetRequests?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken&SpotFleetRequestId=SpotFleetRequestId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the specified Spot fleet requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1078d53-a4b6-4a39-b5f7-230135d7d7e0"
            }
          ]
        },
        {
          "id": "cac94b22-20e9-463b-b89f-9cd24bb6ce68",
          "name": "modifyspotfleetrequest",
          "request": {
            "url": "http://example.com/api/?Action=ModifySpotFleetRequest?DryRun=DryRun&SpotFleetRequestConfig=SpotFleetRequestConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified Spot fleet request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3b42c3e-3b04-4c41-a670-5977856dea08"
            }
          ]
        },
        {
          "id": "5583d54d-dbde-47b2-aba5-eb148525d9bc",
          "name": "requestspotfleet",
          "request": {
            "url": "http://example.com/api/?Action=RequestSpotFleet?Ipv6CidrBlock=Ipv6CidrBlock&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a Spot fleet request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a82f8418-4029-43d0-b471-37715879a8a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Instance",
      "item": [
        {
          "id": "274e584e-4d95-4bbb-86fb-49f2736ef7a8",
          "name": "describespotfleetinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotFleetInstances?DryRun=DryRun&EventType=EventType&MaxResults=MaxResults&NextToken=NextToken&SpotFleetRequestId=SpotFleetRequestId&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the running instances for the specified Spot fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33f5eade-7c38-4d46-b7cf-42e58d7489db"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Request History",
      "item": [
        {
          "id": "0e9fa161-2ad9-4278-82b5-6be98ebd901b",
          "name": "describespotfleetrequesthistory",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotFleetRequestHistory?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken&SpotFleetRequestId.N=SpotFleetRequestId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the events for the specified Spot fleet request during the specified time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a80930f2-75d0-4858-ac48-eec9d15d48a5"
            }
          ]
        }
      ]
    },
    {
      "name": "Sport Fleet Requests",
      "item": [
        {
          "id": "a88734ae-2c30-4407-b197-edb16f06b948",
          "name": "describespotfleetrequests",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotFleetRequests",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Spot fleet requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f099482f-16f9-48e7-8ece-76f5b131b59c"
            }
          ]
        }
      ]
    },
    {
      "name": "CIDR Block",
      "item": [
        {
          "id": "0da6bd67-b331-4193-bdba-89bd8bf527d0",
          "name": "associatesubnetcidrblock",
          "request": {
            "url": "http://example.com/api/?Action=AssociateSubnetCidrBlock?AvailabilityZone=AvailabilityZone&CidrBlock=CidrBlock&DryRun=DryRun&Ipv6CidrBlock=Ipv6CidrBlock&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a CIDR block with your subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dac98d42-fae4-4e34-a297-c12aaf92f80c"
            }
          ]
        },
        {
          "id": "d9feadaf-5fc2-4e03-bd0f-bfe3a78499b6",
          "name": "disassociatesubnetcidrblock",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateSubnetCidrBlock?AssignIpv6AddressOnCreation=AssignIpv6AddressOnCreation&MapPublicIpOnLaunch=MapPublicIpOnLaunch&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a CIDR block from a subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00b2070c-c00d-468b-b304-36c199421458"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnets",
      "item": [
        {
          "id": "a141eb2a-58f3-4005-b5a0-851c197b76aa",
          "name": "describesubnets",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSubnets?AssociationId=AssociationId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your subnets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89f67315-6b92-4e7e-86a2-e1f57bcc6144"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "812d8cac-b120-4159-ad73-8ff4b02708a8",
          "name": "createtags",
          "request": {
            "url": "http://example.com/api/?Action=CreateTags?DryRun=DryRun&ResourceId.N=ResourceId.N&Tag.N=Tag.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or overwrites one or more tags for the specified Amazon EC2 resource or\n         resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7da8e9fd-0ebd-4991-aceb-3da260bdf455"
            }
          ]
        },
        {
          "id": "b63e936f-9908-48e9-b611-c4e0cdcc6d12",
          "name": "deletetags",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTags?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified set of tags from the specified set of resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d359df01-89ac-4141-a7e7-170a63186e1f"
            }
          ]
        },
        {
          "id": "268902df-19da-4ca8-bf7e-2317673f7172",
          "name": "describetags",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTags?ConversionTaskId=ConversionTaskId&DryRun=DryRun&ReasonMessage=ReasonMessage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the tags for your EC2 resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7617172-0d27-45d7-95ec-67e53abb7723"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Task",
      "item": [
        {
          "id": "5ed43a92-d5f1-4d69-80c4-e81c77ae7ac9",
          "name": "cancelimporttask",
          "request": {
            "url": "http://example.com/api/?Action=CancelImportTask?ConversionTaskId.N=ConversionTaskId.N&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an in-process import virtual machine or import snapshot task."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df8ea30b-a83d-4c97-b5c7-f7b7533e462c"
            }
          ]
        }
      ]
    },
    {
      "name": "Version Tasks",
      "item": [
        {
          "id": "80081f04-ef0a-4895-ae69-9423890810b3",
          "name": "describeconversiontasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConversionTasks",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your conversion tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f028110-82e4-4d1c-9029-99457dbef80e"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image Tasks",
      "item": [
        {
          "id": "4b4e6650-eb5a-440b-95dc-16ac5a982812",
          "name": "describeimportimagetasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImportImageTasks",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Displays details about an import virtual machine or import snapshot tasks that are already created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "168214b5-54f0-4ace-bde5-704aa9dbd6df"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Snapshot Takss",
      "item": [
        {
          "id": "7295cc68-ec1c-4838-9221-141ddf8963dc",
          "name": "describeimportsnapshottasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImportSnapshotTasks?Description=Description&DiskImage.N=DiskImage.N&DryRun=DryRun&LaunchSpecification=LaunchSpecification&Platform=Platform",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your import snapshot tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe05989e-00d3-4a6e-9650-a0bac0126647"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image",
      "item": [
        {
          "id": "80d51913-a8c3-4d39-89da-8f7bff092f3b",
          "name": "importimage",
          "request": {
            "url": "http://example.com/api/?Action=ImportImage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Displays details about an import virtual machine or import snapshot tasks that are already created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d38284fb-3708-45ff-9193-228ae83f5d36"
            }
          ]
        }
      ]
    }
  ]
}