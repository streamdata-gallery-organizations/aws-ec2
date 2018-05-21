{
  "info": {
    "name": "AWS EC2 API Create Subnet",
    "_postman_id": "12b84486-51cf-4811-a56b-119ca5025be9",
    "description": "Creates a subnet in an existing VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "a3fa24e2-2976-40cf-87e6-3aadaa9581b1",
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
              "id": "00c2e5b8-752b-4134-b22c-2e6817e06e97"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "a08de918-edd7-4963-9fd0-71de81aecb2b",
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
              "id": "426b5e29-2905-4e8d-8e7e-d0d9450580bd"
            }
          ]
        },
        {
          "id": "ac9deaeb-563f-4f68-b5d0-da9f57c59326",
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
              "id": "80358c70-d796-4be5-b7c4-5b47a060fdc6"
            }
          ]
        },
        {
          "id": "2d505279-24cb-4ddd-bf69-1434b0fe138f",
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
              "id": "4c3fa106-9c41-4190-9f70-61f3013e4459"
            }
          ]
        },
        {
          "id": "2dfa5210-f34c-46f0-8347-0ed90e67d21d",
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
              "id": "af63313d-8c09-47ec-ab00-42f377b61a55"
            }
          ]
        },
        {
          "id": "eb3f1d1d-4ec6-4596-93ac-6a2fcf59f2e0",
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
              "id": "44c12d46-1ef9-4e22-86c9-f73a50d4247a"
            }
          ]
        },
        {
          "id": "fc3a5fdf-628f-4cd4-b8eb-0b2c59c95a93",
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
              "id": "28e941c0-9d29-49ce-b9ad-629abf6252cb"
            }
          ]
        },
        {
          "id": "cd520ac6-588e-40fe-a109-d6b177f39ef8",
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
              "id": "45561094-b3d4-4af7-8826-dc310a0e76c0"
            }
          ]
        },
        {
          "id": "f5d40e84-aa67-4e96-9b5c-954461389ab3",
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
              "id": "2193d445-43bd-484f-ace2-4c7e63691d2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "7736fe7e-0b57-4ef2-9a70-52f1c77820f7",
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
              "id": "33a26b98-1a4a-4415-9d18-09fd3d345b44"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "b20d8e4c-66ce-4c28-8a0e-f2e7c2d93892",
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
              "id": "f4f8a209-a279-4d17-91f2-87949ab2adb4"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "cf28bc35-8f41-4fb0-bcfb-ad499875cb42",
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
              "id": "46ca1ed9-016f-40d7-aeac-c8c6bb19fd56"
            }
          ]
        },
        {
          "id": "7ca6c552-9cf6-4e10-bfe6-98b01e7f379d",
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
              "id": "0cc3a207-a64d-4ef6-9e06-0f46e52d8a3b"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "16eff3d2-4c64-4868-b7eb-ede0552ef0ee",
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
              "id": "bcdd8256-d5e2-4a6a-83a3-0c31f7ac6d8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "f1949e93-bece-4e56-a5dc-777ccb9accfd",
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
              "id": "0345cfef-028a-45f0-b53d-bb975f6fd32c"
            }
          ]
        },
        {
          "id": "98b1ac68-76df-458e-ab4c-8d8b5f2044a6",
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
              "id": "6d4a55d4-575a-4f52-a60e-2be3126133b7"
            }
          ]
        },
        {
          "id": "c199e1ee-f41d-42fd-9a8d-64af3cb4c383",
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
              "id": "8f2f5a53-0da4-4bad-b529-c3a08eb58a5a"
            }
          ]
        },
        {
          "id": "9c4c9c82-1059-4370-a3d1-1739634562b2",
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
              "id": "81eeb967-6b89-4a4e-9824-bd991ca69657"
            }
          ]
        },
        {
          "id": "967274aa-603e-4ee1-99e9-0e79422b23f1",
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
              "id": "5cab6909-e76c-4489-82bc-e70db8ef1da6"
            }
          ]
        },
        {
          "id": "3375f550-8ae8-4ee2-9801-855fd211882d",
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
              "id": "06f9ddc1-45c9-47d2-84d9-10e944c03830"
            }
          ]
        },
        {
          "id": "85355568-8d90-4789-a479-83ef2396c94f",
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
              "id": "d0c2866a-a116-4f82-9c4b-e918699b89ee"
            }
          ]
        },
        {
          "id": "8d97f3b0-73e9-44c8-861c-32d1ef2be545",
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
              "id": "38948bf7-2016-431b-8491-00088abdf75b"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "7f90af70-c16d-4550-8d54-5f8af63bdcd3",
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
              "id": "877a80e0-588c-41cc-a596-6c8154c14777"
            }
          ]
        },
        {
          "id": "04e74507-e85c-477e-abe1-1797efae0764",
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
              "id": "49ec6122-ac80-469f-a879-52ea2a8c5d23"
            }
          ]
        },
        {
          "id": "86d659ce-3401-4fcd-b506-87dc551bdd68",
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
              "id": "efeadc0d-fabf-48ee-ae09-d804acbcd9c6"
            }
          ]
        },
        {
          "id": "00b4ed4a-d976-400b-a8fe-be6c7a5bace6",
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
              "id": "f9d7aae5-f833-49eb-9321-9a9d15e53656"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "6d1f718c-e854-4094-a56f-29ed56612260",
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
              "id": "629f1248-7df8-482d-8599-d11c62de51ec"
            }
          ]
        },
        {
          "id": "13e677a5-f88a-4310-aaba-78990df82702",
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
              "id": "db340e74-c89c-49b6-893f-4202e341213e"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "66b44146-4869-4791-84fa-81b48083bdee",
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
              "id": "3a358254-49d0-4a24-a203-5befb6b26a1f"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "883b9dbc-1d8e-4965-8022-d7b02dc46e4d",
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
              "id": "a52b085b-7204-4342-8246-c203a23b35e6"
            }
          ]
        },
        {
          "id": "71b69904-d111-44a4-9968-ee8d478e797d",
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
              "id": "63080587-64c2-45ad-bce2-96d17215843c"
            }
          ]
        },
        {
          "id": "f0d65375-5c50-40f5-9d4a-4b43dd1fa2b8",
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
              "id": "2fa942d8-f687-4e4b-8816-23db5d8ae5d5"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "9613fff9-a5b8-4cdc-855a-caaf13f07ddd",
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
              "id": "698b3572-a785-4d66-942c-edd04ec19e54"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "a377219b-0368-4973-8e63-ac43a3ef7a1d",
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
              "id": "953d0f2e-12db-4cba-8895-9e68a39864fe"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "d829b17d-f4ec-4879-8899-8d6d71cf5536",
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
              "id": "35602d1b-e5e3-4c42-9f03-0db325a82762"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "fbfb67c5-b2b2-41d0-b53e-ff56c2dd9b94",
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
              "id": "f86c3816-0861-47ed-a2ea-8881083feab7"
            }
          ]
        },
        {
          "id": "b7956942-53f3-4c49-aaab-436d20634415",
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
              "id": "b62ad0c2-3138-4390-98e8-2d60fc0f0cf1"
            }
          ]
        },
        {
          "id": "002ce6d7-1ed9-4797-8997-f95fc3995be6",
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
              "id": "956fba1b-54dc-4d1a-9e2d-d33e26fb6943"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "4332693f-8bab-4a78-94df-4d6e7637fd2d",
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
              "id": "5aaa3185-404b-4578-a61a-51588bdc0665"
            }
          ]
        },
        {
          "id": "2ab49b73-9132-49fd-b935-c4767fb323ff",
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
              "id": "7bab9efb-95ec-4ccd-ab98-665dcc7395ab"
            }
          ]
        },
        {
          "id": "662192a2-0eb4-437e-bc53-6229015f28ab",
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
              "id": "a40e49f1-99f3-4d63-862f-a7f551606e22"
            }
          ]
        },
        {
          "id": "bbb85af4-88c1-49f1-bff3-242686a47284",
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
              "id": "f58861da-c48e-4be2-af5d-c8cf1e2d6303"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "a68e722c-675e-4543-bcd2-0aa2752e6773",
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
              "id": "3b0a5bee-5709-4f29-8b83-a8b27505f374"
            }
          ]
        },
        {
          "id": "b6c7ca0d-2980-47bd-babc-75f2f013473c",
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
              "id": "c7cd1ded-32b0-45ad-8cc1-dab68123352f"
            }
          ]
        },
        {
          "id": "24864933-8feb-40a6-8427-9d3a8aa99d05",
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
              "id": "7b08ab5a-eda0-4257-866c-78a9d283c791"
            }
          ]
        },
        {
          "id": "2522aafc-7d6f-4ddb-8777-37c9cf2f660c",
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
              "id": "72141e3a-90f1-4c06-9af2-d28ead2cb2e4"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "4c78dac7-9c09-4f9d-9fac-effd5c6e04d6",
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
              "id": "8b9838bd-b07a-491e-8466-1ad2e12d0604"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "c825f043-1c28-4f9a-8469-8faa71d00272",
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
              "id": "27548fe4-b172-4a8c-975f-3884823c73a0"
            }
          ]
        },
        {
          "id": "49d53eb4-5308-49e0-ba9a-e8d7b27ad210",
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
              "id": "7694e176-45b9-4457-b443-96fff258675a"
            }
          ]
        },
        {
          "id": "96c61c87-94ff-469b-9662-6efb75d80571",
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
              "id": "9f84b7b3-7bec-49ef-95c5-c275a2b824b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "7a501220-f51f-41d7-99f9-23e149d9648c",
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
              "id": "a0d01a4a-2af3-4290-b370-568f6a12793f"
            }
          ]
        },
        {
          "id": "610e5cf1-cf0a-44b4-b59e-9f781985deb1",
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
              "id": "0c5af5c7-37ad-49a1-a449-2ebf2da1d955"
            }
          ]
        },
        {
          "id": "c5ef5af2-4782-4120-adf4-1450308097b0",
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
              "id": "c1055f0c-b7cb-4c76-9ce7-27c0961bbab9"
            }
          ]
        },
        {
          "id": "470fca19-a604-4b4b-a09d-86cf39bcbe18",
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
              "id": "1e04ed23-09e2-43ff-b4b3-edab993bd7cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "f2d7a99e-d015-40f0-b71f-110dabed1ba5",
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
              "id": "2900e5b1-82fa-4d1c-b76c-419619b6d7e7"
            }
          ]
        },
        {
          "id": "d96ead5f-c3e1-4337-a1e6-5af9677b3324",
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
              "id": "4ea87c24-7424-4677-a4df-048582cad425"
            }
          ]
        },
        {
          "id": "ca239d28-7a93-4147-b73c-6bba8c3d4731",
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
              "id": "def8ef27-f8f4-40dc-8b4f-51cbb65a9090"
            }
          ]
        },
        {
          "id": "d9171604-5458-4901-8e5d-c5c64725845a",
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
              "id": "3cb1cd45-8ce4-4003-a9e7-ceabe1906357"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "8ca89252-e9bc-4ea7-bb29-1242cbdc814e",
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
              "id": "78dd3b4a-3a9f-477b-91cb-90ccd8e7dddf"
            }
          ]
        },
        {
          "id": "689f7c2f-4178-4430-bdd4-78546529c00e",
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
              "id": "605fad2a-2551-4b17-bf65-f90b00777baa"
            }
          ]
        },
        {
          "id": "e87e3d10-842c-4966-9c63-041c0d9a897e",
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
              "id": "94fa2db7-1521-4c4d-bef8-56e89d9ed5af"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "84ca9758-1da6-4361-87ef-96247271642c",
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
              "id": "95c09ccb-ec02-4049-b2fa-e65a61bac5c7"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "c777529d-a468-46d6-b2b9-bdd5c53cbf8a",
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
              "id": "5263303e-67c0-49dd-8a04-7fd2d816db16"
            }
          ]
        },
        {
          "id": "9ac1fdb3-7a99-4287-8ac9-6d0213a74cc4",
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
              "id": "cd5ece03-79f8-43e5-aefa-042152a03331"
            }
          ]
        },
        {
          "id": "de2ea914-42f4-4d3e-a653-23cb3ad1238e",
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
              "id": "b4e15ce7-938c-48be-92b1-1a710bbc040f"
            }
          ]
        },
        {
          "id": "4535ea95-96c1-430c-a03a-b9fd24560f06",
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
              "id": "6d48925c-dc76-4b17-8b64-8d984f330a35"
            }
          ]
        },
        {
          "id": "44aaa178-124c-4c28-a35d-520aaa776b79",
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
              "id": "b86dfa19-f332-4245-9133-632aa788fcec"
            }
          ]
        },
        {
          "id": "70a55507-a75c-46e9-af24-019e9a32095e",
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
              "id": "4419b783-24dc-4f80-b8a6-338ed451ea7f"
            }
          ]
        },
        {
          "id": "78ba30e6-3d49-49bf-a82e-a1dc8a8d9b85",
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
              "id": "ea2adb3c-f342-4e7d-85ee-96af0d454b22"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "adec1e9e-28df-4d1d-a35c-dba79e43801f",
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
              "id": "5f1e6a1c-c70c-4f24-a5ff-89c2766fca29"
            }
          ]
        },
        {
          "id": "db32bdfb-cb57-42c3-969d-94f461a581ae",
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
              "id": "eadf502d-c526-4a25-8e94-d08b75aa97fb"
            }
          ]
        },
        {
          "id": "0786c178-9068-4f71-b318-b23a8b5869ac",
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
              "id": "a2bb337b-4034-4fde-bef3-aebb0c884093"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "64edc4d1-f313-4e36-a99b-da68467d2864",
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
              "id": "281854b2-cc61-447a-ad79-ea8617ca2de4"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "05bf1ce5-00d7-48f0-ab10-4696171697e2",
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
              "id": "da784466-2d95-4ad0-ba71-4fa8c174b0b1"
            }
          ]
        },
        {
          "id": "c6d675c1-09da-4a6a-9fca-536ee6b2912b",
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
              "id": "40f25baa-3ea9-4678-b050-f5d17b13d888"
            }
          ]
        },
        {
          "id": "795128f0-5cde-42ad-bc1c-24f9376ea8ad",
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
              "id": "83f6d65d-e572-40f0-a4b0-bd107d12386a"
            }
          ]
        },
        {
          "id": "3a555e18-1a00-4e3b-9cea-600fe2808797",
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
              "id": "1856a1c7-95e9-4a67-88cd-cf9235358dd4"
            }
          ]
        },
        {
          "id": "2a0aaf6c-3f3a-43d6-8323-459640971470",
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
              "id": "4c7eebc0-9844-4a61-a6e0-ac5d28cc2e5a"
            }
          ]
        },
        {
          "id": "588882ee-50bb-4f5d-9267-c2d7bc4cb3df",
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
              "id": "500c413e-7a64-46dc-a738-013e6a802cc7"
            }
          ]
        },
        {
          "id": "5f63238b-6aec-44ce-ae01-fe8f79c53565",
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
              "id": "59bd2d4e-6c5b-4b1d-956a-885a8650159e"
            }
          ]
        },
        {
          "id": "58e7f001-8cef-45fd-ac00-d646911a3ae2",
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
              "id": "6d5d6cc3-2819-4651-93c6-6635e0c00e7e"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "c058b5bf-64c9-49af-886e-524fa126d072",
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
              "id": "b76e6702-f4ec-4aff-8058-bf0393b969f2"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "e7e0964c-fdc3-40ef-bcea-173cb0992c1b",
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
              "id": "8874d247-1368-4c83-a753-f15b05422105"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "da803f6a-7742-46d0-a729-6cf913fe2396",
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
              "id": "230f1269-b82c-4a8d-871c-31ea431dae53"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "92c579c1-cfa7-4d3c-9795-bbc886ac01d6",
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
              "id": "407362d5-4024-41b0-b0c6-6b93dc02cb3c"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "d754c0d3-5da3-4c54-b47e-9d5ed68fa7bd",
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
              "id": "c57cecd0-b5f2-4763-96d9-f1c4b7fc2acc"
            }
          ]
        }
      ]
    },
    {
      "name": "Monitor Instance",
      "item": [
        {
          "id": "131ca4fb-28e3-473a-8431-13032090766a",
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
              "id": "cca431f5-85c5-468f-8a58-c3c15cf8fe03"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance",
      "item": [
        {
          "id": "6eed52a9-87c3-41cc-bf6d-6ab9ea33a7a3",
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
              "id": "69f47347-601f-413e-9717-269f9b7b3af7"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "4b262244-89d8-4d5d-8237-3378a0e2faf0",
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
              "id": "0acdc4d0-3bb5-46ad-b616-a8d7ba17a5e2"
            }
          ]
        },
        {
          "id": "eace8138-1546-4d30-af5b-e9aaa42e465e",
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
              "id": "072e65a2-53d6-484c-a85a-fbf29d4b6071"
            }
          ]
        },
        {
          "id": "4ebe2a63-71b4-4cac-9a4b-e3c0e6898b6d",
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
              "id": "1297557c-c5ba-451b-8c00-42d251ac5df0"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminal Instances",
      "item": [
        {
          "id": "700df39f-5e11-49a5-9d0c-b6d71ad32d9a",
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
              "id": "7918070f-b743-4bdf-a4a4-5f9ff6520304"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateway",
      "item": [
        {
          "id": "ccc1b6e9-f190-45b4-80c3-69b4abf5fadd",
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
              "id": "213c1c68-c21e-4282-b39a-c28610992a7a"
            }
          ]
        },
        {
          "id": "f6fad60e-62f4-4070-9381-e8f1b247c9a5",
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
              "id": "f28f76d5-3c5d-4315-b715-9c2ff326e44b"
            }
          ]
        },
        {
          "id": "6eac72fc-738e-40c3-b33d-3ec59b75c204",
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
              "id": "a8f21b02-e949-46ad-8938-a110d9aa2bf8"
            }
          ]
        },
        {
          "id": "4c7a24e3-b5d1-4bc0-89e1-7a75483c2630",
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
              "id": "5e524c75-df49-49ec-8fae-29977e5019d4"
            }
          ]
        },
        {
          "id": "dcf8814f-6691-4cf7-be2f-a09cd68cc9cf",
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
              "id": "fcdf3264-e879-4484-86aa-addbd5a9f264"
            }
          ]
        },
        {
          "id": "525a4397-5950-41dc-b460-6121916932c1",
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
              "id": "c4388ba2-9111-4b8e-99c6-372c37c92608"
            }
          ]
        },
        {
          "id": "86391071-f6d4-4192-b281-3274bcb33c4b",
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
              "id": "e7baacda-2589-4018-b4cc-1485c6ee671b"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateways",
      "item": [
        {
          "id": "dea2c1f1-70f6-431c-a915-7aab5b2f7e0d",
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
              "id": "39b6416b-5c80-4fa3-8777-7fb60f4832d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pair",
      "item": [
        {
          "id": "c47a8962-b444-45c2-8504-59a7a56e1856",
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
              "id": "8fe8ee63-73c5-47e1-a87d-19b6edb08401"
            }
          ]
        },
        {
          "id": "f8dc3c0b-9f4a-4af3-ac5c-02a3ecbcd8c4",
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
              "id": "e0596841-2feb-455b-8177-6e502ad8b1a5"
            }
          ]
        },
        {
          "id": "6a55bbe6-0b2c-44d9-831a-f49ac5d33c26",
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
              "id": "aaf55ccb-49e8-4da5-b296-530785b29b50"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Paris",
      "item": [
        {
          "id": "98f02bd7-c998-4592-aca3-e1d8dfd75ab1",
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
              "id": "0bc56edb-65be-40df-8d71-6f8b846720f4"
            }
          ]
        }
      ]
    },
    {
      "name": "NAT Gateways",
      "item": [
        {
          "id": "4a6c5a99-8838-46b3-8d99-ebd1bf637056",
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
              "id": "6a779eec-450b-4e88-8e86-4faa199ddf31"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC ACL",
      "item": [
        {
          "id": "7af2d64f-1dc1-4b19-a3d1-d181ad7700bd",
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
              "id": "f4689798-66ea-4f83-92b5-96c8c488b8ae"
            }
          ]
        },
        {
          "id": "c27497a7-7c99-4a0e-862b-b0d79597998b",
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
              "id": "e4bee9d5-bf27-46ee-b674-bfbe86265fa4"
            }
          ]
        }
      ]
    },
    {
      "name": "Network ACL",
      "item": [
        {
          "id": "ac06d1b0-fb39-4a99-9f0a-cb6d0a0b063a",
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
              "id": "462b34d2-24c8-4f0a-928d-025ef9453b18"
            }
          ]
        },
        {
          "id": "e952ee74-1ac7-4f77-a6f7-2266f8197b18",
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
              "id": "ef7d0358-4406-4189-8c38-9fbce0e3d601"
            }
          ]
        },
        {
          "id": "fa4b1d49-74d4-4dd6-acf0-9d8123bddf77",
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
              "id": "2cbb87d1-bb10-4966-9f04-8ed554fa6282"
            }
          ]
        },
        {
          "id": "41fdbf10-fad9-48b8-b0b3-3915ffd9e540",
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
              "id": "f37007c7-c21b-4f8f-958d-7c748e5ee6b0"
            }
          ]
        },
        {
          "id": "fa3dc1a4-c1e2-468c-b8b5-ac2a0f13c65a",
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
              "id": "782fd128-5788-4c5f-aa56-fae9cf3ce226"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Group",
      "item": [
        {
          "id": "3d6df0af-1662-4d18-bb12-e523f2546ed5",
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
              "id": "cdcefbbb-7fc5-43d8-bb56-5fd33ca66a53"
            }
          ]
        },
        {
          "id": "ea5ee63d-aa70-4936-814b-1d599df7f86f",
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
              "id": "f9ab883d-641a-4751-95b3-bc5bbed025a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Groups",
      "item": [
        {
          "id": "97ccca4a-02eb-4c83-8392-4d7ae8fbafa2",
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
              "id": "ad72f023-6603-456f-af0c-dccfce09b18a"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Zones",
      "item": [
        {
          "id": "fe6f85a0-34de-4ed3-b774-39141ab9cb53",
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
              "id": "e6d359d9-4cf5-4adc-b567-c13e35fe212f"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "b142d7b0-82c5-44e1-81f6-7dfc106b186c",
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
              "id": "7b0e1cc2-09cc-4f63-a65f-1ed1de9c5d7a"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instances",
      "item": [
        {
          "id": "b76725ad-7aa1-4b7c-a651-ef59c6de904b",
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
              "id": "f3fbfe3c-a12b-4d89-8549-a0122d75bfed"
            }
          ]
        },
        {
          "id": "e5ea349d-a60a-4c3f-8dcc-6fafc58d6078",
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
              "id": "afbb9ca3-3bd2-46d9-8ee4-e999d2d9b778"
            }
          ]
        },
        {
          "id": "f27c86b8-b144-4e89-ab63-f8c664c3cbe1",
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
              "id": "9e148457-315c-41c1-af8e-f2ce3c2be718"
            }
          ]
        },
        {
          "id": "561ddcf7-bb90-419e-b0fa-d27aa8781ce3",
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
              "id": "674f1278-65ef-4f83-a725-bf8e403653d3"
            }
          ]
        },
        {
          "id": "37a2d2c0-b366-4f10-9109-b556f51d88e3",
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
              "id": "f3c93d7c-1791-453e-aadc-349b582cb8b2"
            }
          ]
        },
        {
          "id": "b3477185-28fd-4ea3-a074-c245554a3db1",
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
              "id": "29a3ed87-e259-46d3-a78e-25afbcf849f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instance",
      "item": [
        {
          "id": "f0394d6f-83ed-413f-92e1-eac0adb0cc7a",
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
              "id": "b6762b43-e2cb-461f-a822-87415ddd204b"
            }
          ]
        },
        {
          "id": "98f2557c-01e2-456f-8253-f3849f513432",
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
              "id": "a3b19c83-8be4-4ab0-9030-a50bff3a670c"
            }
          ]
        },
        {
          "id": "8d0a16b7-2af2-4af0-bdc1-4e18385b3370",
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
              "id": "1dd6d5cd-6526-4ecf-b88b-2cdaeff67847"
            }
          ]
        },
        {
          "id": "48dce01d-f13d-4ecd-b251-6fe287293da4",
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
              "id": "75a9090f-2610-463e-9158-b7cf45eb94e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Format",
      "item": [
        {
          "id": "a462685f-37f5-4935-9c3f-7a7e2f39519b",
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
              "id": "78d15feb-84c0-492b-ac98-c92e54c352f9"
            }
          ]
        },
        {
          "id": "ac65c0fa-ca2d-4066-8c8a-2cd9c10b4e7f",
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
              "id": "eb015b8b-f17a-4425-8e02-6bbb1789a900"
            }
          ]
        },
        {
          "id": "5d84a847-9b6b-4b51-8b0a-437b8276e01f",
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
              "id": "6be71348-3dbb-46a2-ac42-6190f1468bf2"
            }
          ]
        },
        {
          "id": "5c819cbe-d391-45ab-bfbb-9db754a0e903",
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
              "id": "03c60235-8cb5-498c-b961-742e0047927c"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Table",
      "item": [
        {
          "id": "0fd26ef2-801a-4202-8b98-f1082c8dd9f7",
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
              "id": "cee46097-5192-4d01-8e0d-83ed770cadb5"
            }
          ]
        },
        {
          "id": "5672f174-62ee-4cb5-ad88-b5ceebe6577c",
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
              "id": "137ef14d-d787-497c-b871-2022af932d72"
            }
          ]
        },
        {
          "id": "562f8427-a1e3-45c7-bb67-14ff711f2663",
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
              "id": "b7464c02-66c4-4171-9b6a-5c4a85eb77d1"
            }
          ]
        },
        {
          "id": "9fbaadac-1d24-45f5-a068-870f1c06141d",
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
              "id": "f848979f-4960-41e7-827d-ac8164aad9e5"
            }
          ]
        },
        {
          "id": "313ee8c4-357a-48f2-be5b-62e27e8c36a1",
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
              "id": "99d2054f-4219-48e7-8f0f-75228aaba270"
            }
          ]
        },
        {
          "id": "75ab0ed0-14e0-4d5c-803f-8305908c70b8",
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
              "id": "24f2bc46-0b8a-47cb-a629-bf90af6a1f17"
            }
          ]
        }
      ]
    },
    {
      "name": "Route",
      "item": [
        {
          "id": "0270ee1e-f607-4692-8a17-16604dc225fc",
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
              "id": "0864d39c-9c97-44c6-81c5-dafad6f67c46"
            }
          ]
        },
        {
          "id": "57d20c03-cbd1-4c96-8b60-b2e7cad0008d",
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
              "id": "273691fb-5298-45e2-975b-238c86a285ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "21ea5a50-5365-45ae-afda-482362b530eb",
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
              "id": "09c20c94-4825-42e4-a88a-acd1b5157498"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway",
      "item": [
        {
          "id": "fd4c9f97-d767-4c1e-8918-2c581747d346",
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
              "id": "ebd366b4-289d-4635-9ff2-d16fdcaa1a4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway Route Propogation",
      "item": [
        {
          "id": "30ce945b-64cf-4064-ade8-d96cbd466dea",
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
              "id": "4f36e254-7fcc-4b3a-985c-ac7f3e6b4cec"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Availability",
      "item": [
        {
          "id": "3d21c7ed-6e62-4b13-86cb-1442df09e1a1",
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
              "id": "a2a635cd-2f3a-4877-9789-42b264ff9e67"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Server Instances",
      "item": [
        {
          "id": "fe4047ee-6b81-46e2-81ab-4680759e7dfc",
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
              "id": "eee395b3-f270-46bf-91b5-b3867f36b922"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instance",
      "item": [
        {
          "id": "86b3dcf6-191d-497e-9171-bde1626504a2",
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
              "id": "bf059822-98f2-41e5-984d-dfe8e784159c"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instances",
      "item": [
        {
          "id": "34c5d05f-d163-4dce-933e-64dc36b91126",
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
              "id": "6386cd15-0a13-4ddc-bad7-4c840783456f"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Group",
      "item": [
        {
          "id": "d8e406e2-87f2-45ee-8f2a-313270e007b2",
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
              "id": "a6e6e1d3-7511-4cb7-9769-86b077236cf5"
            }
          ]
        },
        {
          "id": "e7173bb7-a418-47bb-8ade-7ebb122b5e9b",
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
              "id": "a23a92fa-ed25-4f2f-9617-66371767bda5"
            }
          ]
        },
        {
          "id": "4e2060ce-7c87-4149-84a5-2894ecec18aa",
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
              "id": "6b2d2fb3-1bdf-492b-94e1-d2cf14a3a0c9"
            }
          ]
        },
        {
          "id": "9f6cc3a0-8b56-4611-8b1a-4be330e77415",
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
              "id": "d50e59d0-3561-4316-8271-0ea0942c45ca"
            }
          ]
        },
        {
          "id": "8d3d3a6f-9dfb-4b8a-80f2-caaeef996a67",
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
              "id": "55cb10f0-2141-45bd-a045-c4e47902853f"
            }
          ]
        }
      ]
    },
    {
      "name": "Security  Group",
      "item": [
        {
          "id": "cc7a3904-c019-4b43-8d2f-8956f5b19f74",
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
              "id": "b6ad1ab1-f579-4075-a68e-78558306a9c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Groups",
      "item": [
        {
          "id": "acdcc666-456a-4af5-9696-cf8c813efa82",
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
              "id": "ed276d19-0531-4cce-8e0f-18fd9850f8b1"
            }
          ]
        },
        {
          "id": "833ef412-3d1c-4f98-9d29-3fed62677644",
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
              "id": "fdc53813-b34f-4962-a16e-87e1a0f46927"
            }
          ]
        },
        {
          "id": "b3b48366-c9f9-43fd-9d47-a26fdaf1cae2",
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
              "id": "723d35eb-c0df-41a6-96e5-77a2c37cba6f"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance",
      "item": [
        {
          "id": "c991bf16-9d5f-4539-82f3-93b256599f77",
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
              "id": "006780e0-1b66-4a8b-ab69-f416b5a7226e"
            }
          ]
        },
        {
          "id": "ca457528-be41-4843-a6a0-cc322b3e9416",
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
              "id": "6e298683-86aa-4b66-8429-640f7240098b"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnet",
      "item": [
        {
          "id": "b725e76c-f052-4d02-a453-928f44b9b0c5",
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
              "id": "89cc0d39-687d-4021-b0e8-784801742f30"
            }
          ]
        },
        {
          "id": "0927b94f-5fcb-4e36-932f-1f834969f4ab",
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
              "id": "b8549f5c-1417-41e5-aba8-4bd383d6e0fa"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed Subscription",
      "item": [
        {
          "id": "d894e316-a7d8-4451-81c0-964e422ab2bb",
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
              "id": "213dc3a9-9422-4564-a5c9-339f0b96fce3"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed",
      "item": [
        {
          "id": "7c7ac4d2-369d-40f2-88a4-03d4225ff192",
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
              "id": "831553f8-674d-4fa6-b328-b14b01a9650e"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "015441b6-bd52-41a8-833c-5ef08104e009",
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
              "id": "c8edb937-5219-4846-afe7-8946f7f12658"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Price History",
      "item": [
        {
          "id": "7270662b-05b2-4bd1-b0c9-0986eefdc653",
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
              "id": "08db3be3-d9bc-4bfa-849e-2b69d2e47e94"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet",
      "item": [
        {
          "id": "3ac8fdfb-c4af-4608-b645-c42731df8f0c",
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
              "id": "8a84bedd-cacd-4e2b-922c-9b86839d9171"
            }
          ]
        },
        {
          "id": "687e87ab-6a51-4ea4-85c0-cf6313a38383",
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
              "id": "ed60c410-2bd4-4b2b-a54a-8cb48b318426"
            }
          ]
        },
        {
          "id": "c2f6366a-10bc-4acf-a58a-b2ceab0bf8dc",
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
              "id": "35492e99-5945-43aa-a307-5c05bff6a857"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Instance",
      "item": [
        {
          "id": "0ffaa2f9-f5f4-4557-a1f4-975ef48ee62c",
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
              "id": "3428754b-58ff-4f87-ae72-71fee91bc3af"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Request History",
      "item": [
        {
          "id": "4489f9cf-6bf5-465a-8e09-41c5b44f650b",
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
              "id": "f5062ae1-1ca8-4634-ad26-2e8a6587c5de"
            }
          ]
        }
      ]
    },
    {
      "name": "Sport Fleet Requests",
      "item": [
        {
          "id": "531c856b-a98b-41f5-9e8d-307b84e35c96",
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
              "id": "e8d225c6-b3ca-4c46-8009-b1e8e6ef9c5c"
            }
          ]
        }
      ]
    },
    {
      "name": "CIDR Block",
      "item": [
        {
          "id": "7fbf90b2-e442-4fce-8018-beaa4950f28c",
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
              "id": "84edcfa5-3522-468d-b213-3e518e1163ab"
            }
          ]
        }
      ]
    }
  ]
}