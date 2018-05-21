{
  "info": {
    "name": "AWS EC2 API Create Vpc Peering Connection",
    "_postman_id": "8d317790-44bc-4794-847b-176462753e6b",
    "description": "Requests a VPC peering connection between two VPCs: a requester VPC that you own and a peer VPC with which to create the connection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "efaf8650-c911-4307-be67-8f89f50ece67",
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
              "id": "eb103146-79af-43a1-b6b3-171aa9ef3a70"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "20f4b12a-eeed-4f63-a8a2-bda1d76ff9d4",
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
              "id": "8dd23171-213d-45ba-a2bf-03eb2fcfaeca"
            }
          ]
        },
        {
          "id": "d653b6cf-e07d-4a66-900b-6c2b132abb6b",
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
              "id": "24a37a14-0a5a-4f1c-b22c-c34cddd6c051"
            }
          ]
        },
        {
          "id": "57569161-6d4b-4ce1-a3a5-4ef68ca71d8b",
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
              "id": "dab17af8-15a7-4260-b97a-325df518a7d2"
            }
          ]
        },
        {
          "id": "df832094-ab70-4597-94b1-f353c51951ff",
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
              "id": "7390ab1a-d53c-4161-a8a6-8e81c5907017"
            }
          ]
        },
        {
          "id": "a2e5dbd2-f269-4dd2-b175-fd8ba707527a",
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
              "id": "26adaea3-568f-4ec3-a2ae-e98f6e89b165"
            }
          ]
        },
        {
          "id": "bcd102a4-8050-4a07-81ee-9c49e0b13047",
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
              "id": "3b3e0d5c-9fd9-4974-b5c8-154b70ad4354"
            }
          ]
        },
        {
          "id": "24591ae0-aabd-4911-bd19-2c5503bfff27",
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
              "id": "76e2358d-e740-414c-89b3-3fb9e1323ef6"
            }
          ]
        },
        {
          "id": "7570a1ba-0b7e-4ec9-a9e7-829ccc68090f",
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
              "id": "ecd77c29-6aff-410f-9799-d9fe3cafb555"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "09ec81ff-2676-4f39-b796-031d1ba55a79",
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
              "id": "c9aaa5e0-1e97-450a-94fd-2a9b1f43d1a5"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "eca29131-17af-420f-a003-0539ce14329e",
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
              "id": "24e40016-314f-4597-9804-8a2af0fb2a11"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "8170e0f9-d37b-4867-b0c7-112927b42606",
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
              "id": "2a1488b9-af6e-4a61-a4af-4b18b9b8100a"
            }
          ]
        },
        {
          "id": "542cd06e-780b-4d5f-93d9-32f504a45075",
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
              "id": "195aaec1-0e37-44a9-83f4-46d93e22057f"
            }
          ]
        },
        {
          "id": "8ff60eaf-e444-43cc-8f03-c9173003448d",
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
              "id": "eeae995c-d91b-4015-810e-a5d064242d3d"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "a955ff9c-9fff-4f11-9658-d06597563437",
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
              "id": "59184228-e90b-4e01-a655-c674c9c272b1"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "5f6b3a60-2326-4a25-b505-05bd74bc3938",
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
              "id": "1fb734fe-103e-43db-ba03-6a631534398b"
            }
          ]
        },
        {
          "id": "07e4ff37-cae2-4ef6-baa8-8d65d7426a29",
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
              "id": "ee25dbdd-65fb-4a17-891e-4ff31a62e121"
            }
          ]
        },
        {
          "id": "8cda7314-6c6c-48d2-a521-a03d3e21762c",
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
              "id": "b6ce76b0-6389-4d97-babf-e3c35de48585"
            }
          ]
        },
        {
          "id": "6bd39b0b-f6a2-47a2-ad2b-aac6183ad190",
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
              "id": "1d5be886-30b0-4755-872c-27c961427829"
            }
          ]
        },
        {
          "id": "cde946c2-b7bd-4397-97c0-7e2afa878576",
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
              "id": "d995b96f-3529-4507-9dd5-5dd6aa49bdb1"
            }
          ]
        },
        {
          "id": "eb790f5d-27de-40c4-94e5-c2a6b011ef84",
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
              "id": "e12ea011-d438-4eb4-846a-81c32e07e228"
            }
          ]
        },
        {
          "id": "1234174f-450c-49c4-b8cd-7fd223f0ee96",
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
              "id": "ad41c244-51ae-4e83-a8dd-e955d44efdd9"
            }
          ]
        },
        {
          "id": "4df2306d-3f82-4cb9-bd39-34eaf32c5e5e",
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
              "id": "84df7716-65fb-4171-a7d7-4f3c7706f7fc"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "e0a94e1a-5c3d-45b0-8341-61be7da8ec73",
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
              "id": "2c6e872d-f2f3-4844-880d-d9b4eae2e507"
            }
          ]
        },
        {
          "id": "e0d955a2-6b85-4d0f-be70-f99e89af0771",
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
              "id": "2128446e-0460-4e20-9c4f-d9465ebc81d1"
            }
          ]
        },
        {
          "id": "dbbdbe9c-9868-4f33-859d-73d46e39e91b",
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
              "id": "57af7884-d222-4a76-9c78-092083827f67"
            }
          ]
        },
        {
          "id": "ec331107-98e8-4fa3-9758-3de1c64ca8db",
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
              "id": "b810e9a7-26b5-462f-93f5-d213cee7a973"
            }
          ]
        },
        {
          "id": "506577f1-7857-43ae-856c-cc49e9c703d8",
          "name": "createvpc",
          "request": {
            "url": "http://example.com/api/?Action=CreateVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a VPC with the specified IPv4 CIDR block."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e41abb84-029b-4d11-b859-b953ef33f60d"
            }
          ]
        },
        {
          "id": "0a89faba-1105-4821-980f-628122da0151",
          "name": "deletevpc",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVpc?Attribute=Attribute&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de84398a-9c66-4f46-a4fd-46c8a286d1fe"
            }
          ]
        },
        {
          "id": "1e12edd5-7f2e-4ba3-bac4-bfaeda01ae13",
          "name": "describevpcattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcAttribute?DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c525abd2-0f95-4f19-8f57-fe98b6b8b700"
            }
          ]
        },
        {
          "id": "d77725ce-717d-4e5c-9055-84413f38ed3f",
          "name": "describevpcs",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcs?AssociationId=AssociationId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27cc2695-81ac-45a4-a53a-f0931a0bccf9"
            }
          ]
        },
        {
          "id": "f45b84c8-122b-48ca-a2bf-6420fd24b289",
          "name": "modifyvpcattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVpcAttribute?ClientToken=ClientToken&DeliverLogsPermissionArn=DeliverLogsPermissionArn&LogGroupName=LogGroupName&ResourceId.N=ResourceId.N&ResourceType=ResourceType&TrafficType=TrafficType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c90d718-ee72-4ce5-b5d0-bf73069507af"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "c87aa33c-358b-4ff4-9d4b-c735b6f9bb39",
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
              "id": "d99e6005-6c7c-4d25-a83b-076d869ab6e3"
            }
          ]
        },
        {
          "id": "109074b2-8863-4bf4-bade-1b6b231a9cd8",
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
              "id": "a2468b98-0dc1-4f3f-b7a0-6dffd802d13c"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "35e3f669-a611-4884-b33f-f944850e90f1",
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
              "id": "418cc39b-e18f-4f4d-bf88-e191d10bee66"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "431dc201-d08c-405b-85b4-a591460d920e",
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
              "id": "7e155ca3-4324-4303-b6ad-edbc97afe22f"
            }
          ]
        },
        {
          "id": "8e77ccd4-722e-4464-abbf-1b05cb431b1c",
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
              "id": "4e62f76d-709a-49ba-a219-41a47d00ba17"
            }
          ]
        },
        {
          "id": "02c4847e-cca1-4adb-9d77-b314bf650b16",
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
              "id": "6544d33e-7adb-465f-9edf-e2a327658c0c"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "12488cb1-6c79-4109-bd78-6e1da47d9a4e",
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
              "id": "d85a684b-595c-46ae-8c20-0d0f6254a2aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "81e85f06-8e90-4c70-8289-adb683900d9c",
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
              "id": "b3751255-aa96-49e0-bce5-2485e68a8c09"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "274dae6d-8faa-4a5f-87b7-d661e9b9812f",
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
              "id": "02b60b50-0075-46df-83c0-9d90fb5bb15a"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "58c8a343-2b28-4673-8aba-2d612a979459",
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
              "id": "1456898d-288a-4b5b-95f3-c8f5a8a475dd"
            }
          ]
        },
        {
          "id": "cdc85bc0-561e-4892-a2f4-223fa4191c0a",
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
              "id": "e81570d1-49d8-4a68-bd7c-d3ee591e54d6"
            }
          ]
        },
        {
          "id": "897b7b65-c2b6-4eea-965d-a0ff0bee7669",
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
              "id": "3e7ae4d0-3178-46a7-8383-d267f5feda4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "53987e4c-f001-4108-8650-20e5c6808229",
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
              "id": "1a204eb7-81e5-4a74-808e-9eb30689d30c"
            }
          ]
        },
        {
          "id": "7862ecc2-5868-43d0-bc01-571087e51e25",
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
              "id": "c3366dcf-b5a3-4730-8739-42b5b8052312"
            }
          ]
        },
        {
          "id": "7d670da6-fcc3-4f16-81c6-275bb83daf03",
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
              "id": "2e565270-32ec-4475-9502-cd695aedfc09"
            }
          ]
        },
        {
          "id": "a2bf847d-8162-4cff-9c13-0ef1087d33b0",
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
              "id": "3bec09b1-476e-457e-91d5-24a8d517abff"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "855d7d55-f1eb-43ce-82c3-bd5ec2c097a1",
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
              "id": "07df59f3-9c79-4289-92b5-85d4c1a9096e"
            }
          ]
        },
        {
          "id": "179965aa-98a6-400a-a406-4e281e5e9a5b",
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
              "id": "19780ec3-3cf0-4db9-90de-a42917a6f264"
            }
          ]
        },
        {
          "id": "0f384bf5-aef5-4537-978f-f1800a083633",
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
              "id": "a1c38da9-6d62-4166-b035-6f51e1b386ef"
            }
          ]
        },
        {
          "id": "696f9c42-5f06-4cf8-b3ba-779f4ca46445",
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
              "id": "c2455d52-7985-41e1-9d4b-c1ab9fb709e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "8ea164e3-29e3-4272-afe6-4046f131c401",
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
              "id": "a39541e9-f9d6-48dc-ab5d-38ac2937607b"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "7f5073f6-1afc-4639-9413-f98be6387249",
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
              "id": "6cd443c4-1f21-4cab-87ec-ef16428eec07"
            }
          ]
        },
        {
          "id": "bad586a1-e6cc-4d12-9fa3-9cc6b779d050",
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
              "id": "d15012f5-0b24-4245-b4ed-7537a4020682"
            }
          ]
        },
        {
          "id": "1d1437d5-0daf-4aa6-b7df-c62bba188578",
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
              "id": "118551ff-c075-438e-8b50-d421d297ba28"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "fbd82b5b-c132-46fb-b80e-a32a7480275f",
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
              "id": "98e5593b-e507-46ed-94b2-87545eb2ae68"
            }
          ]
        },
        {
          "id": "e1bd207d-2f4c-433d-8f7b-ed69ca8e32b1",
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
              "id": "71503cd7-bfd2-4f81-bb6d-0c524962bea5"
            }
          ]
        },
        {
          "id": "4c9134f8-ec53-4268-a93e-1cf885dbdf94",
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
              "id": "a2239333-3160-49da-a8c4-de7558e36e37"
            }
          ]
        },
        {
          "id": "cecd0458-287d-4f44-bc67-ae335883d3b0",
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
              "id": "d877b1ad-8c69-4556-80fe-1a141869ce1c"
            }
          ]
        },
        {
          "id": "a7c6a148-cab6-4f2c-b761-c042dee8d4d2",
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
              "id": "acba1f46-99ef-47be-8dac-86446cac31c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "6fc97cd3-32c2-4486-a7bb-aec87ea16c83",
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
              "id": "a27987a0-2b1c-41a4-be00-ed7f3dbc65ff"
            }
          ]
        },
        {
          "id": "644654c3-8864-4741-837e-a997033c627b",
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
              "id": "a1b0fc74-9757-46ec-9497-aba52c13100f"
            }
          ]
        },
        {
          "id": "6f826ff8-b4cf-48a3-ae70-3f50e262a051",
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
              "id": "93de4ce2-8a08-47e0-8ab3-6801ef107ac3"
            }
          ]
        },
        {
          "id": "70a36ca8-cf46-468d-bd36-11352a03a221",
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
              "id": "1d3aeec2-e3a3-4f4a-9756-9e638a80b887"
            }
          ]
        },
        {
          "id": "7b7a5729-cef9-4338-a5f5-d46aef9744a6",
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
              "id": "3f102ce7-3eec-4d7e-8188-3117c37e7556"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "06349d4f-f952-4809-85ea-ab63e841c946",
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
              "id": "95ccdbaf-5e63-4313-b739-a21954a80d36"
            }
          ]
        },
        {
          "id": "694b162e-0452-40ee-b5a7-e0b2e54b97b4",
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
              "id": "e7e4872d-8752-4830-97ec-711f03529cbd"
            }
          ]
        },
        {
          "id": "1bb06453-d714-4732-a9fb-609ad1bed82f",
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
              "id": "7f5ae277-1e02-415d-87e0-9974a4a197b3"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "63c52c33-4e78-458e-a20c-7634d2c38e3b",
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
              "id": "f5e422a2-7afb-4c08-87f0-bf2e7148f5ec"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "607e63c0-b7e2-4d46-ac3c-4b598bf4e03e",
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
              "id": "d77319fa-6815-4411-a95d-2aed14656d19"
            }
          ]
        },
        {
          "id": "55236403-d7ac-4106-a437-b1512bae28a1",
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
              "id": "c5b6b1f9-1c1f-492c-8267-7b2116e3f881"
            }
          ]
        },
        {
          "id": "7c007d86-10cf-4b53-8c17-9e5de48d5d19",
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
              "id": "00832b22-1233-409a-aff9-f100d0b26f27"
            }
          ]
        },
        {
          "id": "f5d59551-2b34-47ba-a0a5-6a8b84b644e5",
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
              "id": "af886631-2c86-4f37-ba07-e2f50ebe580b"
            }
          ]
        },
        {
          "id": "8963aa6d-d9ca-494e-bf2e-57f85c10f09c",
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
              "id": "80812902-a6a0-402a-8962-268818535e68"
            }
          ]
        },
        {
          "id": "7beb5fef-faae-4a7d-b56d-4a5ac8ebbf54",
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
              "id": "f68558e3-73c6-4ce1-ba70-bf5e2acf11ed"
            }
          ]
        },
        {
          "id": "7fff34cf-9f1a-4943-bda5-1e7e383f6c68",
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
              "id": "ca6fda57-4bcf-4735-bf6b-219808444b48"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "9634b820-dfaf-4732-8dfe-4f9bb71c85a2",
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
              "id": "b88e7226-7c83-4f0a-909c-8f9ce1403bed"
            }
          ]
        },
        {
          "id": "770214ea-ae22-417d-bc1f-eeeaeea66e54",
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
              "id": "614f6ed6-89df-4dc4-9ace-ac824a211dc8"
            }
          ]
        },
        {
          "id": "07fe1993-9c2e-4409-9361-cd40272af7f1",
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
              "id": "4494cbf8-1238-4f5e-85a4-1b265bf638aa"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "9075a90d-b3fe-49a8-b2c8-af93756e75af",
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
              "id": "93a14e41-3a90-4acb-8c6b-97f5e4b35b8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "1df076f8-7b2b-4490-98ac-c2a8575635e0",
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
              "id": "b64f1383-c604-4e6c-bed4-a52ffcc64736"
            }
          ]
        },
        {
          "id": "fc490c98-4188-40e0-8d37-b4d62c7de3f9",
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
              "id": "612d3a6b-519b-4df8-b0bc-4463660018e9"
            }
          ]
        },
        {
          "id": "913d0fa7-30ff-4094-bbf5-e279a20a83ad",
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
              "id": "286cca7d-13ae-4e25-a76c-69618557822a"
            }
          ]
        },
        {
          "id": "749e8771-d4ac-4657-bc61-de605a8c0db9",
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
              "id": "0a76e222-b7cf-47b4-8ffa-03ea114e64d5"
            }
          ]
        },
        {
          "id": "4e78e3fb-305d-49fc-936a-5c5f1151768b",
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
              "id": "ec3aac42-20d8-44b5-92a5-3a1810134a70"
            }
          ]
        },
        {
          "id": "34a4951e-8f7b-4d06-825c-e41945dbe9a5",
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
              "id": "6153d2da-c795-42be-a8d7-ed6525384693"
            }
          ]
        },
        {
          "id": "73f6a584-0f34-4f6c-b335-2a31e2a8800d",
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
              "id": "7719ed7d-780b-4a31-8c53-177a04110b8d"
            }
          ]
        },
        {
          "id": "ea75dc34-145d-4c17-a0d8-a8c94dd3e5f1",
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
              "id": "41743987-b091-4f5d-accc-c671a0ab7259"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "0019435f-9d6a-441e-ae24-c3b35e549750",
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
              "id": "fbef9a65-19f0-45ca-9395-d06ce7ee80a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "db543030-3e18-44f5-b0e8-aacefce374eb",
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
              "id": "b06a19b7-0473-4c10-9581-7c0fae55c779"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "ae205bed-58c2-4b14-8a6f-75b45605c627",
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
              "id": "c5f70a8c-0062-4f76-9179-cd3f7e37e8df"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "8870a57d-f015-401e-a474-11f625be5a2a",
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
              "id": "ee0d78eb-d6b7-47e9-a73f-02eea3f5a3eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "710a4116-4b00-4af8-9a96-6399624b6c82",
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
              "id": "ffde328d-1fba-4790-9a09-b7fd74384327"
            }
          ]
        }
      ]
    },
    {
      "name": "Monitor Instance",
      "item": [
        {
          "id": "6dcc09bb-9176-4201-8b44-7b77bb2b4c2d",
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
              "id": "efec79fe-962c-48f7-a784-9c82c6c666ee"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance",
      "item": [
        {
          "id": "f919d91b-6c75-42dc-a271-bfe1603813ac",
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
              "id": "c6b9b99a-e0a6-4ce5-a065-32c668160e89"
            }
          ]
        },
        {
          "id": "061e7b02-c690-4173-b3cd-e8bd65884bbc",
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
              "id": "e5f2598f-6cc2-4628-86a9-a6c36608691c"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "79f253e3-a4ba-43c7-97b3-917a6827d431",
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
              "id": "53ab5476-af05-4b44-8bee-1d40795c8fff"
            }
          ]
        },
        {
          "id": "02757af6-31b4-4f84-b30f-e247b7a884f8",
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
              "id": "5d44de76-f069-415b-9a18-3ab80a56353b"
            }
          ]
        },
        {
          "id": "567b3c19-7c73-4132-861b-8e5fd2921441",
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
              "id": "a79d3576-e6ba-4b0f-bf07-777470a0f2c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminal Instances",
      "item": [
        {
          "id": "878c3645-f321-4104-b4b0-e2d7f7615a62",
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
              "id": "650ac237-565a-4909-9bdd-e334662fcefe"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateway",
      "item": [
        {
          "id": "0b6d65a5-7e32-400b-9f2a-bd6887ddfab2",
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
              "id": "014fb4a7-e61c-4ec5-8e3e-7c5550e44912"
            }
          ]
        },
        {
          "id": "1a28b098-31f4-4011-95e7-d77248cc2e69",
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
              "id": "332e74e6-4b6b-4b9d-a824-c0f8b4954168"
            }
          ]
        },
        {
          "id": "1a802bd4-5212-49c2-8cad-ea986ea1bb48",
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
              "id": "21983352-f81a-4cc3-af15-8e0728d399a8"
            }
          ]
        },
        {
          "id": "58337b18-40a7-46b0-b8cc-7c9cad470b04",
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
              "id": "dcbf91f1-f19c-417d-a4fa-fb5c51468354"
            }
          ]
        },
        {
          "id": "fb73ed65-d051-4f00-a1ca-c43ceadbaeb6",
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
              "id": "39927abd-c824-4fd2-8146-9088ba0a07ed"
            }
          ]
        },
        {
          "id": "89d1d0ee-307f-439b-9799-b05de88421ce",
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
              "id": "d7cba8d5-3b89-4cd7-8cc6-66501ac6aeca"
            }
          ]
        },
        {
          "id": "bf2d21ad-cd7e-4f1e-9c48-70a696dc9d3f",
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
              "id": "fa38dfac-8322-495d-ba96-5ebaae4bb339"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateways",
      "item": [
        {
          "id": "04a308d1-b2d3-46f5-93e6-ce84fced29b3",
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
              "id": "cf5e5c8d-5f0f-4959-8352-9040dd25928d"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pair",
      "item": [
        {
          "id": "972a103f-7b46-4d13-a58a-a2e689cd6b15",
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
              "id": "6093f51e-2e7b-4a46-84b4-feed0a0ee7e6"
            }
          ]
        },
        {
          "id": "2a106912-d4fb-4705-879d-436674a30cf4",
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
              "id": "dc2f9717-6398-4ec2-9327-f53996bd4662"
            }
          ]
        },
        {
          "id": "3256c309-fe08-4f4b-a838-56e4792c0353",
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
              "id": "55dfd005-8de3-474a-b46c-0e996a8267b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Paris",
      "item": [
        {
          "id": "8654b8ca-6238-44ff-9f32-439004697090",
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
              "id": "4f9e8150-1468-4cee-8d5b-aaaa7d25200e"
            }
          ]
        }
      ]
    },
    {
      "name": "NAT Gateways",
      "item": [
        {
          "id": "24f0084a-c9f9-4cfb-b646-e860b12ec47b",
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
              "id": "1d86f14d-85b9-445a-967d-8800d54f25de"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC ACL",
      "item": [
        {
          "id": "1c971c45-83d0-4430-96a4-1eb77b022a3f",
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
              "id": "bfcc8108-2506-40c2-8f33-058ed9615acc"
            }
          ]
        },
        {
          "id": "f05fc4a0-19fb-45f9-9ad4-4eaf33bf0e23",
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
              "id": "6b86112e-92ce-478c-8970-dc9bbaa33a1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Network ACL",
      "item": [
        {
          "id": "3ea0d2a8-b561-49a7-b2ed-3ef23856142f",
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
              "id": "3a612610-62ba-4b98-b3a5-bcfb297ee98f"
            }
          ]
        },
        {
          "id": "f324ad02-8de0-47d7-b0b1-11b0086f37fd",
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
              "id": "f69e2aad-6597-426a-93be-ecff784e3b7e"
            }
          ]
        },
        {
          "id": "d007dfe7-45f1-4c28-a6c5-a4b0c5ad88ff",
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
              "id": "f852dbc2-1ccb-45d2-982a-ff7b4b477392"
            }
          ]
        },
        {
          "id": "7e610c18-139e-4950-8e19-b6df0488d9f2",
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
              "id": "e27f5109-9cb4-42b9-b389-cac3c9ab3f28"
            }
          ]
        },
        {
          "id": "f37e0dce-ec66-429f-bb19-6de21c72d38f",
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
              "id": "7b2d5329-b2c8-41a9-a67c-a7b57dc27145"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Group",
      "item": [
        {
          "id": "b4d7f8af-b028-4ac9-97a8-4eb7924bcf34",
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
              "id": "83e5b84a-259f-4a6c-8775-7074a174f2cf"
            }
          ]
        },
        {
          "id": "2d1f3dfd-a2f2-4c03-b41b-011afbe33a43",
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
              "id": "c8361aeb-047c-4d5f-9530-88e78c302860"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Groups",
      "item": [
        {
          "id": "c20d3070-5a74-4748-be50-2a2355dd64fe",
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
              "id": "e40fb4dd-de84-4993-b4ef-75ed8647cf7f"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Zones",
      "item": [
        {
          "id": "8f15eeb3-61ef-4070-b542-445254ca894e",
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
              "id": "2acfe092-b327-4ac4-a1e2-396179719a76"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "230dad80-2453-47c1-bb1b-6a688600944c",
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
              "id": "1939d3a8-b387-40b4-8ff3-75db22f79baa"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instances",
      "item": [
        {
          "id": "ef18fa71-ab1a-4d24-bd54-45355fdc27d0",
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
              "id": "f80538c6-0906-4fb8-9a85-52ccc6407f69"
            }
          ]
        },
        {
          "id": "973973f4-f959-4116-8660-83173c94803a",
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
              "id": "beeae01e-2401-4302-82b1-b2d03d980124"
            }
          ]
        },
        {
          "id": "989f35c1-7a01-4ce7-9daf-7ba0cec969f4",
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
              "id": "4a7d95df-cfa3-4b4e-937e-c88193100ac1"
            }
          ]
        },
        {
          "id": "1d379635-d1f8-4dc5-86e5-ccfdcd704917",
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
              "id": "00a99aa6-b252-4d67-aa64-f075b5cef4be"
            }
          ]
        },
        {
          "id": "5bd66966-b311-4ab5-b440-1363b6953c92",
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
              "id": "67de6e0e-4842-47d3-a234-808a6eec4871"
            }
          ]
        },
        {
          "id": "6d3af2c1-7437-410f-81fb-d60389680842",
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
              "id": "cbdd6a2c-3e8b-4380-aad0-139b3deb0bb5"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instance",
      "item": [
        {
          "id": "0ad50fee-435c-478b-9c20-96e97349fa05",
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
              "id": "45771188-17fc-48d2-b430-24ba5bd6e86d"
            }
          ]
        },
        {
          "id": "08fb314e-2b61-4fb2-9f7b-b96de08fad4c",
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
              "id": "687b2d09-02e2-4876-9369-0993780f5836"
            }
          ]
        },
        {
          "id": "bdf9a39e-66d1-4008-86ed-c31597dcc360",
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
              "id": "694116d0-e4d3-440c-b9b5-3600ff4d978f"
            }
          ]
        },
        {
          "id": "c4a3a82b-b600-45bf-9aed-86b7006a5be1",
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
              "id": "4c10922a-a9b1-47b3-9ed8-904066917c90"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Format",
      "item": [
        {
          "id": "ba05d510-b526-4c7d-924f-225c3b855b02",
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
              "id": "ea73b9c0-e2ae-4716-8e6b-202259ef27b0"
            }
          ]
        },
        {
          "id": "1ec1e9f8-3e74-40cc-94a2-bd71280c4e00",
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
              "id": "9e983fea-e766-4d2c-95fd-d63f7b619ad2"
            }
          ]
        },
        {
          "id": "28ecf83a-b730-405b-952b-4201bc813848",
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
              "id": "072e8c3c-c840-4145-9ac8-4c4472167fc8"
            }
          ]
        },
        {
          "id": "3a525b24-c72c-4a10-a723-9efb9404eabf",
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
              "id": "7eda6c18-31c3-46f6-80a3-557117df771a"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Table",
      "item": [
        {
          "id": "f90b9bd9-bcb9-4e64-9e40-cca2bfb7f102",
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
              "id": "c5846892-f0bb-4d1f-9ae4-a61979de09a7"
            }
          ]
        },
        {
          "id": "a0c65c65-fc97-4411-970b-29f0c0dc9445",
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
              "id": "3f317919-5e9a-47f1-bc27-033b9dc9ddf8"
            }
          ]
        },
        {
          "id": "920c5774-9433-4605-a601-95758ff7994b",
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
              "id": "4ab43da6-68b3-4f2f-8592-3f0e5adaf600"
            }
          ]
        },
        {
          "id": "e7ced2b0-368e-4fd5-9a83-6f36ed33b569",
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
              "id": "6ce74c2c-f0a2-4a43-9871-e6a7ecfb6f0f"
            }
          ]
        },
        {
          "id": "cbc68729-9b4c-4846-b7a6-2447a6c80070",
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
              "id": "d0b673fd-37d6-4ab9-8e81-6d623ba2d31b"
            }
          ]
        },
        {
          "id": "cb1752ce-4268-4bde-a077-0c424c0f83e9",
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
              "id": "e35b60cb-0c60-4af4-91f6-7c69c4d2abf6"
            }
          ]
        }
      ]
    },
    {
      "name": "Route",
      "item": [
        {
          "id": "2b460b47-f26a-414d-b876-a448fb15158c",
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
              "id": "dcf6fcb4-5c9e-4bf0-ba0c-c1ae5e9af286"
            }
          ]
        },
        {
          "id": "49f0fd12-d0be-47ac-8bee-3119987877f2",
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
              "id": "379b6445-a0f3-4ac9-8c4c-f9ebcaedcc54"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "8e6c5be3-ad24-42c5-b69c-9ab518272faa",
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
              "id": "9b64f302-07a0-42ad-8332-ce300d4c9c92"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway",
      "item": [
        {
          "id": "18371747-2054-493c-ac55-49bd1c828ce2",
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
              "id": "1c2f20cd-9896-498b-8391-e4e99fcdd435"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway Route Propogation",
      "item": [
        {
          "id": "efae0548-d719-46f3-934e-46f6f6ef31f6",
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
              "id": "53b93fea-8251-4415-b37f-3a6429852155"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Availability",
      "item": [
        {
          "id": "2af4686d-e272-409f-b8f7-f0e8d38106ea",
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
              "id": "06716ddc-7183-43ad-8d1e-522ff033c230"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Server Instances",
      "item": [
        {
          "id": "a54f9ce9-2ffe-4698-9ea4-7ccae92ff7ed",
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
              "id": "fdf67922-04c1-4e8a-ba15-e0accdee7a32"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instance",
      "item": [
        {
          "id": "3c4782ea-fcbe-4a89-95ab-2f7096b2e407",
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
              "id": "2e25b3dc-1ab4-45c2-9d64-7a898dc03e22"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instances",
      "item": [
        {
          "id": "7d538724-6d3e-493a-8ed8-6eeb2afbeee8",
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
              "id": "0227ebc3-4b03-48f4-a32c-d089e1af7f46"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Group",
      "item": [
        {
          "id": "f3af9696-402f-444b-903a-820474c77f34",
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
              "id": "1c06df14-d731-42d0-af1a-d90f085fbddc"
            }
          ]
        },
        {
          "id": "074be2ba-e622-4c20-a1ca-fc071faf07da",
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
              "id": "55aa0b99-2a1f-4713-9b5c-c0b82bd987a0"
            }
          ]
        },
        {
          "id": "110def9c-5028-4666-9a25-6adcaa091432",
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
              "id": "d81fb07b-ce39-46a1-b91a-a4d0294ac8b9"
            }
          ]
        },
        {
          "id": "b01a082c-ef2f-4b1e-8213-3825ed403552",
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
              "id": "d65ed748-6857-4ee2-ac1f-45ee98e9ff72"
            }
          ]
        },
        {
          "id": "83ce2d21-1159-4576-864d-eb110ffb8eb8",
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
              "id": "fbf250cd-5384-49ba-ae87-4f84e94623c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Security  Group",
      "item": [
        {
          "id": "8c71bc1f-0918-44a2-8e52-f8575e3fbbc6",
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
              "id": "7c844cdb-9965-45fc-98a1-5ab13a78dc4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Groups",
      "item": [
        {
          "id": "e0148bff-31c2-402b-b6a3-1141d10c91e6",
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
              "id": "f32e371c-2d4b-4130-aaef-10c8f8f7f8d2"
            }
          ]
        },
        {
          "id": "e874a333-2130-4ed1-843b-002ebdd0a3d7",
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
              "id": "ef81e4f0-18fc-404d-98c4-ac551b1ec9e0"
            }
          ]
        },
        {
          "id": "98c20ad6-37e2-430b-8d59-b09b018abf41",
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
              "id": "1a2f1e79-b94d-4ce7-b6d2-396d053bcf3c"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance",
      "item": [
        {
          "id": "534eefc6-70f0-4fdb-ab07-10f836576c47",
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
              "id": "72eaf2c8-d8df-4262-9d1e-d6f7e09a9dbf"
            }
          ]
        },
        {
          "id": "668b7c8e-a2e6-491a-9181-ef306b34fe11",
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
              "id": "50168bcc-8c67-45ce-98b2-3fee92a4be44"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnet",
      "item": [
        {
          "id": "f326bb2f-41b1-4efb-8e85-8d9b696c428d",
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
              "id": "3d30fb5a-9e50-4e8f-8f1e-38268d5b340a"
            }
          ]
        },
        {
          "id": "2d092908-0bb0-4fcc-bcb1-7135127b97f0",
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
              "id": "e953f795-d413-4ff5-960d-865da55fd16b"
            }
          ]
        },
        {
          "id": "6c11258a-c8fb-4c49-83d5-80f053390555",
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
              "id": "9331badf-ac79-46f9-bfa3-0aaf9c2b46d4"
            }
          ]
        },
        {
          "id": "006976f2-aa26-444a-a40b-7d15a0b64d39",
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
              "id": "749be1e2-6660-4eaf-8062-112ed3384d46"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed Subscription",
      "item": [
        {
          "id": "ab2d7988-c3dc-48bf-a891-bd7d34911567",
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
              "id": "d316a092-cf5e-4f1c-92c8-950aa773f1f7"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed",
      "item": [
        {
          "id": "672b66a2-9e84-4da2-bad9-b5fccc9acc0e",
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
              "id": "d6af6c14-2110-4268-8ae4-bd429c40642a"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "a1aa2418-6da1-4fb7-8e71-6aac7b1fa165",
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
              "id": "80ff8d52-971f-4b85-ba52-f65fd36e4994"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Price History",
      "item": [
        {
          "id": "4c0d16c2-97f2-4a4c-bf8b-27ad5f4bb2f4",
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
              "id": "9f0fe080-6447-4243-88a1-9c86a4d85e6b"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet",
      "item": [
        {
          "id": "83489431-ff43-422a-bdcd-2eaf65c770d6",
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
              "id": "725172c0-f0d1-4fc9-b383-8c73fec2b6e9"
            }
          ]
        },
        {
          "id": "e921c8f3-0c21-43a2-855c-e2a817a0e752",
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
              "id": "f46fd44c-86a9-4fa7-bf00-987b89a60416"
            }
          ]
        },
        {
          "id": "50031cf9-3992-4831-8aec-23be8ba802dc",
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
              "id": "d1a56eff-e1e5-4572-9d28-73ef19bc4e85"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Instance",
      "item": [
        {
          "id": "2d2fb08d-94b7-4337-8cd7-dad1ff465861",
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
              "id": "b2c9b795-2b60-4702-b1d1-3e5cd0357aff"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Request History",
      "item": [
        {
          "id": "63b25365-31d6-481f-af9b-811e5fca9e2c",
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
              "id": "9a16a2ae-7d44-4834-be04-365c3fbefec6"
            }
          ]
        }
      ]
    },
    {
      "name": "Sport Fleet Requests",
      "item": [
        {
          "id": "e13a2e8f-832b-47be-96a6-31f41b614cab",
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
              "id": "af12bbcb-4755-4778-a841-e64f661301d3"
            }
          ]
        }
      ]
    },
    {
      "name": "CIDR Block",
      "item": [
        {
          "id": "4ccef239-a99c-4e16-a631-efa919684ecd",
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
              "id": "ff57a77d-b5bc-4f5d-b7de-6cc3df42aaac"
            }
          ]
        },
        {
          "id": "abc89072-e56b-4400-b08e-c10ed4ec2fc7",
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
              "id": "1e83900a-4ba8-4dd4-b4ce-05538ac8b6c0"
            }
          ]
        },
        {
          "id": "b8173b59-4e43-40f9-b81c-fef972d6ae0a",
          "name": "associatevpccidrblock",
          "request": {
            "url": "http://example.com/api/?Action=AssociateVpcCidrBlock?AmazonProvidedIpv6CidrBlock=AmazonProvidedIpv6CidrBlock&CidrBlock=CidrBlock&DryRun=DryRun&InstanceTenancy=InstanceTenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a CIDR block with your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c38b4f60-191b-405d-9052-3136c7b0ba83"
            }
          ]
        },
        {
          "id": "93db75b7-1a90-4c1f-8b3f-a7d1cf70da2e",
          "name": "disassociatevpccidrblock",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateVpcCidrBlock?EnableDnsHostnames=EnableDnsHostnames&EnableDnsSupport=EnableDnsSupport&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a CIDR block from a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ba5c9fd-a713-4799-83bc-9023c765418e"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnets",
      "item": [
        {
          "id": "0018b929-de16-43c6-84b7-145bd7157e00",
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
              "id": "015b9058-3da7-405c-8df2-cefc8b149d34"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "0cf7d78d-5483-4008-8c6b-9c7b2d5ae024",
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
              "id": "f324be04-d8b0-40fa-96ee-5b75611f5e87"
            }
          ]
        },
        {
          "id": "ad8efa45-567d-4582-942e-5d3287c9f03a",
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
              "id": "ff95d4ae-3145-48e7-83e0-8482454bac9f"
            }
          ]
        },
        {
          "id": "fe02e278-138a-4259-acbd-488b07a09c55",
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
              "id": "6e19fc48-f4a8-4c72-bdd1-a747a8fef729"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Task",
      "item": [
        {
          "id": "6ed0e944-ca73-406f-b4e5-e03fa8ab5cc6",
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
              "id": "d4ef9a01-3ddf-42c8-bade-aeb6e10e901e"
            }
          ]
        }
      ]
    },
    {
      "name": "Version Tasks",
      "item": [
        {
          "id": "b9c0d108-0512-4cce-8dba-7b8e60312981",
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
              "id": "2adbf276-e033-4e86-a77f-9e52e95213c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image Tasks",
      "item": [
        {
          "id": "9444c54a-83ac-48f5-b7cb-90142c07dc75",
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
              "id": "6af1706d-8ea8-463b-98bc-6f5d6e10cdc5"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Snapshot Takss",
      "item": [
        {
          "id": "f7c345da-c2dd-4af3-8b58-42266d889881",
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
              "id": "34d1d6d2-961a-4507-817f-d38bad408d66"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image",
      "item": [
        {
          "id": "dd753f80-73fa-41b4-bbd2-72a4af926d2b",
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
              "id": "6c494337-acf6-4a61-9f3f-38d5ea347f8b"
            }
          ]
        }
      ]
    },
    {
      "name": "Export Task",
      "item": [
        {
          "id": "02d0afa9-c68c-4342-8541-873b8118f8dd",
          "name": "cancelexporttask",
          "request": {
            "url": "http://example.com/api/?Action=CancelExportTask?Description=Description&ExportToS3=ExportToS3&InstanceId=InstanceId&TargetEnvironment=TargetEnvironment",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an active export task."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f72f23c-5343-4219-9b18-3a3aa508908b"
            }
          ]
        },
        {
          "id": "86310394-d25c-454c-b6f8-4194c4c563e2",
          "name": "createinstanceexporttask",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceExportTask?ExportTaskId.N=ExportTaskId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exports a running or stopped instance to an S3 bucket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37dfc842-b671-40fe-91c1-f24172df0cba"
            }
          ]
        }
      ]
    },
    {
      "name": "Export Takss",
      "item": [
        {
          "id": "a118b45a-f728-4388-b1bc-b1dc55b3e1bc",
          "name": "describeexporttasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeExportTasks?AmazonProvidedIpv6CidrBlock=AmazonProvidedIpv6CidrBlock&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your export tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8038609-52f6-4a0d-9c20-c5691e9cbc2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Flow Logs",
      "item": [
        {
          "id": "868fff69-40db-4007-abcf-06db3258ae83",
          "name": "createflowlogs",
          "request": {
            "url": "http://example.com/api/?Action=CreateFlowLogs?FlowLogId.N=FlowLogId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates one or more flow logs to capture IP traffic for a specific network interface, subnet, or VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9a2e977-028c-4566-b73b-c7237291d89a"
            }
          ]
        },
        {
          "id": "eaa35935-77aa-424d-9b80-523ab6374de4",
          "name": "describeflowlogs",
          "request": {
            "url": "http://example.com/api/?Action=DescribeFlowLogs?ClientToken=ClientToken&DryRun=DryRun&PolicyDocument=PolicyDocument&RouteTableId.N=RouteTableId.N&ServiceName=ServiceName&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more flow logs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7eb1a817-dc54-4760-a237-fe2e396f8206"
            }
          ]
        }
      ]
    },
    {
      "name": "FLow Logs",
      "item": [
        {
          "id": "f45dc65a-420d-4f93-a6b3-4d792ef8ba8a",
          "name": "deleteflowlogs",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFlowLogs?Filter.N=Filter.N&FlowLogId.N=FlowLogId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes one or more flow logs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a4630e7-dfb2-40c9-94f4-db364ff7b304"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Endpoint",
      "item": [
        {
          "id": "ad1f6fd6-c676-4729-8a39-a558b3f06406",
          "name": "createvpcendpoint",
          "request": {
            "url": "http://example.com/api/?Action=CreateVpcEndpoint?DryRun=DryRun&VpcEndpointId.N=VpcEndpointId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a VPC endpoint for a specified AWS service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd842cd8-3f28-4f5b-90ee-99d076a65522"
            }
          ]
        },
        {
          "id": "d9ff65ba-0ed4-43ba-9e89-c8eb43899a7b",
          "name": "modifyvpcendpoint",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVpcEndpoint?DryRun=DryRun&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies attributes of a specified VPC endpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5ec7992-8f76-4ad2-ae75-01559e6d83bf"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Endpoints",
      "item": [
        {
          "id": "f3b6ab12-6f8f-4831-bc1a-1a09ba950a95",
          "name": "deletevpcendpoints",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVpcEndpoints?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&PrefixListId.N=PrefixListId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes one or more specified VPC endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f057505-cb80-4dae-8301-a841d1f60408"
            }
          ]
        },
        {
          "id": "a9f827e5-8cef-4e62-83be-8214490b8c7d",
          "name": "describevpcendpoints",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcEndpoints?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPC endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98bb7c94-f27a-4176-b3a2-184863807adc"
            }
          ]
        }
      ]
    },
    {
      "name": "Prefix List",
      "item": [
        {
          "id": "fd1a236f-6766-4aa3-93f1-6220922e9b19",
          "name": "describeprefixlists",
          "request": {
            "url": "http://example.com/api/?Action=DescribePrefixLists?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VpcEndpointId.N=VpcEndpointId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes available AWS services in a prefix list format, which includes the prefix list name and prefix list ID of the service and the IP address range for the service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c816b47-f3cc-4173-bd66-aae9258dde16"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Endpoint Services",
      "item": [
        {
          "id": "267cb2f2-69c8-47aa-a0f9-65597f647c15",
          "name": "describevpcendpointservices",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcEndpointServices?AddRouteTableId.N=AddRouteTableId.N&DryRun=DryRun&PolicyDocument=PolicyDocument&RemoveRouteTableId.N=RemoveRouteTableId.N&ResetPolicy=ResetPolicy&VpcEndpointId=VpcEndpointId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes all supported AWS services that can be specified when creating a VPC endpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b53b9f2d-0f5a-4046-b815-9afd169c7a8a"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Peering Connection",
      "item": [
        {
          "id": "26f8c53b-aa53-48e0-bf74-99628b2745e9",
          "name": "acceptvpcpeeringconnection",
          "request": {
            "url": "http://example.com/api/?Action=AcceptVpcPeeringConnection?DryRun=DryRun&PeerOwnerId=PeerOwnerId&PeerVpcId=PeerVpcId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accept a VPC peering connection request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "889485c0-d937-4deb-be14-2ad74be181d9"
            }
          ]
        },
        {
          "id": "d90fd4fc-102a-4ebe-91a9-9d9e078d899d",
          "name": "createvpcpeeringconnection",
          "request": {
            "url": "http://example.com/api/?Action=CreateVpcPeeringConnection?DryRun=DryRun&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a VPC peering connection between two VPCs: a requester VPC that you own and a peer VPC with which to create the connection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b46e1d9-04dc-4ada-843b-182558cf1f2e"
            }
          ]
        }
      ]
    }
  ]
}