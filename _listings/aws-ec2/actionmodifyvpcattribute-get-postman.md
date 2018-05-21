{
  "info": {
    "name": "AWS EC2 API Modify Vpc Attribute",
    "_postman_id": "3ac4b138-b9cc-4e98-a20d-5b4c1f3880a1",
    "description": "Modifies the specified attribute of the specified VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "184550e1-8506-4d99-9ff6-0ef68be698e7",
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
              "id": "562bb7ee-f98d-44c7-866e-aa295f1e9b1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "488e54c1-7f7a-4f66-97ae-faff6cb3dcaf",
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
              "id": "fe984a0f-9af1-4c53-8f91-614606296683"
            }
          ]
        },
        {
          "id": "1ba93279-bead-40f7-acf0-171761e0236c",
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
              "id": "d27f1867-9f0d-46b2-87d6-d01e3abbe7a1"
            }
          ]
        },
        {
          "id": "9c7c08ab-d614-4113-8602-d79bf0e9f83e",
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
              "id": "9631e372-5bcc-4313-9cec-ef61283ecc19"
            }
          ]
        },
        {
          "id": "33756e6a-fecb-4cce-8a43-e6f0d2e15461",
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
              "id": "fa07437e-6cb5-4c53-93da-8cb593fa9f7c"
            }
          ]
        },
        {
          "id": "7a8d7a00-553d-4246-aa3b-8f8b4bdabb9b",
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
              "id": "b4cacce0-6384-40e1-ad16-97de72937527"
            }
          ]
        },
        {
          "id": "c9366934-3210-4567-957f-83008e5cc66c",
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
              "id": "663f3c85-4670-40f4-bdbd-9400c3ec7a32"
            }
          ]
        },
        {
          "id": "767efe90-5377-4102-a763-b5f05c13cc37",
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
              "id": "ef32fb14-9b24-4663-ac11-67826514dd6d"
            }
          ]
        },
        {
          "id": "71651917-2102-4fe3-828e-da324d99099a",
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
              "id": "426ee9c5-eb7c-4fd9-b81e-8a39d3821556"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "0bed00d2-d53f-4ccf-b116-6ba4be973c14",
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
              "id": "ac6e7ec1-1ad7-495e-ba6c-9539a68e2ee5"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "6a0a8382-3718-4903-bf93-bbc1c5acb58a",
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
              "id": "0dc02af9-15ac-4381-a71d-778961f056d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "3f30f3a2-79b7-4fc2-859e-26fe4f1cf2c4",
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
              "id": "9c2225b1-9fed-4c37-83e0-f99943dfc1b9"
            }
          ]
        },
        {
          "id": "41460f04-1cb4-479d-97c1-ddbb63abae80",
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
              "id": "cdd74bed-d5db-4d2c-9919-c840191c45d9"
            }
          ]
        },
        {
          "id": "a7435ef0-b861-4836-80ca-c267cff03777",
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
              "id": "71744d72-03a9-4947-bfec-fa13b0ee8671"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "cd22db68-3efc-48e3-8765-8326f3d92430",
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
              "id": "a828bacc-aaf8-4be5-b81b-60e135307ca7"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "831561ac-1e77-4da5-8c97-a76255d7cd29",
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
              "id": "5aafebe9-a1bb-423f-830a-61e19bacc13b"
            }
          ]
        },
        {
          "id": "ac1b2429-db8e-4639-bb8a-6cfed14c028e",
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
              "id": "c45a722b-1964-4ae0-b529-6eb3611cd6bc"
            }
          ]
        },
        {
          "id": "759593e2-2df9-4d1b-84e3-38d70d0d34ae",
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
              "id": "0fc61a02-db0c-4859-beed-6181d394ecb0"
            }
          ]
        },
        {
          "id": "65195439-c064-4f3d-ad31-23e3d667c8f6",
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
              "id": "a698def0-f3c4-4ed5-9325-640cdf2bb085"
            }
          ]
        },
        {
          "id": "cfcc1dc9-cc9e-40be-ac53-7a679646e48f",
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
              "id": "6a1c7289-a63f-4599-b843-9aafc9511cdb"
            }
          ]
        },
        {
          "id": "42981b2b-3bc4-4275-8543-0d3afb57a722",
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
              "id": "3cb1e8bf-9996-4a66-b601-68094f53cad8"
            }
          ]
        },
        {
          "id": "d05e26ef-381c-406d-a307-d29233c15be1",
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
              "id": "ab08b8e3-fe86-4fce-81ad-b0a68fba5ff4"
            }
          ]
        },
        {
          "id": "7546026d-0d9b-4149-b4c4-d6db675930a7",
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
              "id": "9f5cbe13-91ba-4570-b80b-c26574af2393"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "3d7bc92c-4655-4107-a278-01017de3a8b0",
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
              "id": "02fa7a67-9f91-4cc6-b3d5-f8394bf2ab69"
            }
          ]
        },
        {
          "id": "cb2c4f86-2218-445d-b72e-f46d1857c7a3",
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
              "id": "07553f82-19bb-4b3b-8200-6237959c1d7e"
            }
          ]
        },
        {
          "id": "2fa2a77f-6e16-491e-9cec-c068a8b13947",
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
              "id": "12caebce-5845-4637-9989-cd271539057d"
            }
          ]
        },
        {
          "id": "c203c3b1-1f27-42ad-a5bd-997be251d06e",
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
              "id": "db160a6a-53ef-42eb-96ad-0fd6b7f19a97"
            }
          ]
        },
        {
          "id": "0c9ea2e2-e80b-404a-a32b-d648b60aa0ff",
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
              "id": "7edd0864-5351-42fb-9d95-6c83dcd99d9e"
            }
          ]
        },
        {
          "id": "b31dbc8b-db59-4fe8-8870-00c27c9e1f62",
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
              "id": "8c0d9341-9daf-4928-909b-11b0cf794b56"
            }
          ]
        },
        {
          "id": "3374d449-b18b-401e-8599-9cc24ae07fad",
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
              "id": "6e56483b-0131-4a7e-95e2-390bfb6b7b09"
            }
          ]
        },
        {
          "id": "e3cbc866-0245-472b-ade1-7504645377a3",
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
              "id": "94de5732-11d2-4523-be9f-8a6caf581c2d"
            }
          ]
        },
        {
          "id": "8a6a3051-7d20-4e6a-8a44-55e67e63ffcd",
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
              "id": "7c08a2a8-b854-4d9a-85b1-f54630688b7a"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "e889d215-f0e0-49f9-b3e2-f21f6da6fe66",
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
              "id": "df1181c6-49c3-4712-b445-4b9af298fb7e"
            }
          ]
        },
        {
          "id": "dae8d627-2f44-4770-99cb-4ef84f72a766",
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
              "id": "acabe13b-8776-4a45-89f3-370fe3e03f7d"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "9905f5a3-ca21-46ff-9468-d6bad25401b3",
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
              "id": "d68efe62-7d73-48ad-ae76-9bd69cdc49c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "be5f4607-d110-456d-ace7-a44b03cb4bfb",
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
              "id": "c5854d13-0752-4f8a-9417-8f974220bc46"
            }
          ]
        },
        {
          "id": "6f78ed7c-b0a1-4cda-93ce-c9e51955d4d2",
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
              "id": "a1450f70-8ca6-49a3-b6d9-e9ac8c4f4c27"
            }
          ]
        },
        {
          "id": "6a67c866-4efb-424d-b605-b43ba3263457",
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
              "id": "d4776c0f-1c62-462c-8174-d82898d9faf6"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "616776f8-58a1-4694-8745-8fd653f48c3d",
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
              "id": "6b390913-cc7e-4add-b366-98b30f5bfa2d"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "4e5354a0-cfe4-4b4b-bb22-af5f4a48bab8",
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
              "id": "78a11960-abc3-4411-8952-54bb9b47dff6"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "468917ab-e8f6-4b40-9631-bb04bc359a3f",
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
              "id": "4730b873-43c6-4fda-b2f9-7146d244e31d"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "018f5876-1df1-47a0-80c6-bc5a639f4404",
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
              "id": "84271cc7-0463-4ba6-ac49-02dd9cf37e76"
            }
          ]
        },
        {
          "id": "a72bd1c3-2dec-4fe4-a19b-88b93b4fecea",
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
              "id": "187f7f13-f6b5-4ad9-bbeb-7e7e935cdc62"
            }
          ]
        },
        {
          "id": "e66cb2af-4d1d-4ddb-89a4-8329bc3af8ba",
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
              "id": "8f7d4aec-a8c7-4324-9e63-0b0c82388c42"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "75a3cbcc-449d-4269-aadd-69b138638054",
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
              "id": "3bfd1d2c-df8e-49f7-a2c5-4a170b1d58f7"
            }
          ]
        },
        {
          "id": "a500a516-d079-4887-9946-ccbbbafaa528",
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
              "id": "8246752c-dd7d-4828-b304-08a6fdd16e9e"
            }
          ]
        },
        {
          "id": "19cd6cb1-f975-4075-bda6-ab06e2014e8d",
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
              "id": "e99676d8-0781-4d33-a986-ada99265aa7c"
            }
          ]
        },
        {
          "id": "2aa33bb6-3111-47db-a437-fefdfd9c979d",
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
              "id": "c5c23e99-b8b0-417c-9c26-648ff24f5cf2"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "70ba1f23-c53c-4627-ab94-ce9cec651c71",
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
              "id": "6396f2c6-18bf-491b-b3ba-bf582b9e1b0a"
            }
          ]
        },
        {
          "id": "453c3b2c-38c7-496d-96bb-9eedac485257",
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
              "id": "24e14279-cf0b-4812-9047-5f08a7b0ca30"
            }
          ]
        },
        {
          "id": "338ed4db-523b-443d-b663-154ffa6edfce",
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
              "id": "dbf8ffb2-f496-4ba9-8244-b7c3c332bff2"
            }
          ]
        },
        {
          "id": "08d3476b-dce7-4eb8-801d-d0697eacae90",
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
              "id": "2d5dfccb-121a-4f1e-9754-4efd1fb59b16"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "2914a928-3d47-4619-b437-d0f547b8095e",
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
              "id": "cae9bb30-8292-4cb1-83f3-7741a1d6e688"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "ae533874-d355-416a-ac89-dc5cf28c2df8",
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
              "id": "75d69741-2c4e-4648-88d1-fb5d596b2734"
            }
          ]
        },
        {
          "id": "2799a6dd-edec-4af2-ba07-23ee33e4f4b8",
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
              "id": "9667e34a-6ddd-4b2c-bd7a-de080709c84f"
            }
          ]
        },
        {
          "id": "176ddaf0-a874-463f-911c-b94503a48a5b",
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
              "id": "7c3f950c-98e1-46e8-9f35-98d908608aa7"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "6da484d2-8e53-42bf-9cf6-ab3129b1d701",
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
              "id": "f111bd8c-07ee-472c-b88e-8ff76fff5fab"
            }
          ]
        },
        {
          "id": "18de84ac-0b96-4a55-8101-7c41502ead98",
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
              "id": "83da4bbe-fabf-4b58-989d-01938e58ae60"
            }
          ]
        },
        {
          "id": "1adc3a59-ea4e-404c-aaa4-9f65c3a38a83",
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
              "id": "6a45858f-8bf2-48ba-9ccb-957c6bedcdbc"
            }
          ]
        },
        {
          "id": "8df1ce7a-11c9-43d2-8f1a-0a02c32a6d54",
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
              "id": "cabacfdf-f9d1-4b21-97a2-99cfd81406c2"
            }
          ]
        },
        {
          "id": "8bad7b18-ded0-41b2-9c45-cd2cacbb3bc2",
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
              "id": "dbac75cd-0139-49f4-97b3-15498734bcbe"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "658cd5d7-a2cf-4813-a876-a23c871c163a",
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
              "id": "22b4e632-51eb-4347-806e-0637527f65b8"
            }
          ]
        },
        {
          "id": "0212587f-9d51-428d-9957-c79de5a7106e",
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
              "id": "1b93558f-13f0-4366-b4b4-b6e0f0c52e23"
            }
          ]
        },
        {
          "id": "68082508-a1fb-4536-bdcd-e2a14d76cff2",
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
              "id": "1779b2c8-235f-4fc6-bd30-02684c9c63a0"
            }
          ]
        },
        {
          "id": "f8753f5f-1a86-40e5-a7b4-e269b274a8d4",
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
              "id": "67b2625e-b6b7-4386-b342-41ee29fd9aac"
            }
          ]
        },
        {
          "id": "d62bd0fc-6fdb-4107-b344-dec3e7a98c34",
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
              "id": "fef59f00-cb6d-4b9f-bbbd-500bada393fc"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "ffd65e79-6597-47f5-b4b6-6bdb6251a6f4",
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
              "id": "6b312be4-3a85-4a4a-ba0f-8f052d32b54d"
            }
          ]
        },
        {
          "id": "c2677670-873e-45d6-8f88-e2351e4c9ebe",
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
              "id": "7bac6f08-8007-480e-b5fc-0ed702f71180"
            }
          ]
        },
        {
          "id": "2b92e7c8-3d17-4694-8bc9-73ed413b3c59",
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
              "id": "ea0a42fc-37d0-4102-be23-14b00952493a"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "6b633c7b-5d24-471a-8da1-048aecf6b19c",
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
              "id": "b7c914b3-c52d-4d08-9e5d-2b40a4f42d2b"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "c42bcb29-07d1-41f1-9673-f136564ac4fc",
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
              "id": "b6149fda-7e8f-4aac-b753-e94bdd848e64"
            }
          ]
        },
        {
          "id": "7460d5f3-2565-419f-8cb7-a3da99d81c81",
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
              "id": "6b4168ac-bd4b-4e10-93d5-fd44b11f0e17"
            }
          ]
        },
        {
          "id": "74b87dde-f456-4ad4-b338-029c18987196",
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
              "id": "e7f578be-6efa-480d-8b8a-a78d5210e524"
            }
          ]
        },
        {
          "id": "2727936b-c350-470f-ad25-645077683f63",
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
              "id": "3ba81e84-b353-4729-a5de-d168c29b54b7"
            }
          ]
        },
        {
          "id": "5be2f6c6-c858-4a39-8a1c-6336eb47f8df",
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
              "id": "7d3b1be3-dc47-4319-a9d4-3813761c9dfc"
            }
          ]
        },
        {
          "id": "2dfda727-4cfd-442f-b921-e901c0264d14",
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
              "id": "acbc8d13-0dd2-413a-a5fb-622da4b6b16f"
            }
          ]
        },
        {
          "id": "7aaffa65-58c9-49fd-9761-78b615c07642",
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
              "id": "637e86c8-521e-4af3-a0cb-9f7ff5131b97"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "5df42318-5a3d-441a-939c-0ae7f64194a4",
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
              "id": "bb58afa0-7567-445d-87b1-8e155ad785bd"
            }
          ]
        },
        {
          "id": "05d02536-a9c5-4b68-af44-4f1a0e1b2348",
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
              "id": "a4378747-b15f-4082-a538-016cadb07c40"
            }
          ]
        },
        {
          "id": "7009653e-60ba-43ee-a5da-8ee30602ae5e",
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
              "id": "81143214-240c-4f9a-872f-6846aa7cea9b"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "1b458296-763c-46d8-85a8-75bb7fc88b14",
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
              "id": "ed1b6041-208d-4771-b2ff-32e3efdad255"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "4cbaa207-68ef-43ff-94a1-2eb39f64f656",
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
              "id": "8a7794fa-2348-4790-9b1a-53df5abe88d7"
            }
          ]
        },
        {
          "id": "457607eb-11a0-45e2-b5fc-6d257e788778",
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
              "id": "bf8db818-3579-4316-bec4-1892bd376f1d"
            }
          ]
        },
        {
          "id": "9ae6bd6f-dccf-4862-8b03-762a8f52eee5",
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
              "id": "ca40f7fa-582b-4301-8ea7-7813de4c09a8"
            }
          ]
        },
        {
          "id": "59defac8-20ed-4b69-8321-3252bfbb575b",
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
              "id": "4e3ca677-5dce-415b-be60-b4908cdfe657"
            }
          ]
        },
        {
          "id": "e950d62f-da46-4ccb-b193-e11d81d04beb",
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
              "id": "b12edf63-a877-4948-a95d-05387d28ce66"
            }
          ]
        },
        {
          "id": "811c87b7-db8a-488b-ae24-7c018f5fc2da",
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
              "id": "85b74664-898a-4163-a21a-0016ded00c13"
            }
          ]
        },
        {
          "id": "d4a301cc-bcbc-47ed-8443-1a9d5b17b258",
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
              "id": "b6e2da96-1e1e-48b0-abc1-4a19a579d9f2"
            }
          ]
        },
        {
          "id": "652f627c-2da3-49bb-bced-7506f650f295",
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
              "id": "f48db182-e5f4-4803-9d9e-bc1cef6419e3"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "7d6b38e7-9728-44b4-9f39-dd04784b079c",
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
              "id": "a3c5dcd6-4b67-4d84-96a9-19ab14b769b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "d857a193-7772-4d13-b399-0054ff1603e3",
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
              "id": "4b05eeef-003c-4109-820d-66cb9ff82c5c"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "914cc559-78b3-4554-852c-d43d4d7890f9",
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
              "id": "0638db94-d78c-4194-863e-cba0df2fc66b"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "2a3e2708-96f2-431f-880b-5b0abb0d6e83",
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
              "id": "609bfbcc-1333-4899-922a-bf37fdff376f"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "2548dae4-ee19-4398-87b5-30b5a04ae31b",
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
              "id": "59ffe49c-ca14-4f90-9f7c-5808b990767f"
            }
          ]
        }
      ]
    },
    {
      "name": "Monitor Instance",
      "item": [
        {
          "id": "e96073e7-36e8-4a85-891f-cd977ae48976",
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
              "id": "3c3c400a-e5bf-4435-8c21-104a3d8a4606"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance",
      "item": [
        {
          "id": "fc2da3b4-34a9-4c9d-8b84-fc6b0d0d3fa1",
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
              "id": "3d1b5772-528e-470d-bd72-346b2cde5847"
            }
          ]
        },
        {
          "id": "9236a0ff-4527-4238-af55-e921aa84d4c4",
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
              "id": "4506c58f-7b87-4536-88dc-596b63b9b524"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "3100193c-b974-4476-9ec7-10b87ffa0dae",
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
              "id": "0aa40966-4a7b-4354-a14d-70cf6883915e"
            }
          ]
        },
        {
          "id": "fe19743a-ff9b-4fbc-9fbf-43045a868d99",
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
              "id": "4331c38d-7b85-4f3c-a86a-d251c8e21d82"
            }
          ]
        },
        {
          "id": "bf655fe1-96a7-4dcb-8a45-0ad40bfc92ee",
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
              "id": "767df72f-8bbc-4751-8de8-94d97edba8e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminal Instances",
      "item": [
        {
          "id": "490c9ba6-5967-4efb-ab0c-169ba0cf7347",
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
              "id": "96a3961c-4db1-4cd5-a023-1c067ecb85a1"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateway",
      "item": [
        {
          "id": "51c6863a-51bb-458d-83ea-4bb43fae8b2b",
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
              "id": "e8f44c4c-efff-4e48-8b0c-2762123b3afe"
            }
          ]
        },
        {
          "id": "dba8c004-6439-461d-8430-1c4bfb302523",
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
              "id": "f8b38df2-b110-4c5b-927a-d3026e243026"
            }
          ]
        },
        {
          "id": "2d9b92cb-b9ca-4e00-8134-2b862627222b",
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
              "id": "6f8a1678-11d0-4fe6-ac43-48ef53bb9954"
            }
          ]
        },
        {
          "id": "ae7b975d-ffb0-42d1-81a7-65b0cbae1ebb",
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
              "id": "84d1cb99-c851-46a1-aaf0-eb39cdaf8e25"
            }
          ]
        },
        {
          "id": "3d64ba63-b41a-43e7-afbc-ab6bdfa77b37",
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
              "id": "c75611bb-aaec-49f6-bf79-25910510f8f9"
            }
          ]
        },
        {
          "id": "e56784d3-06bf-4a09-abe0-8fdfde81c8ad",
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
              "id": "81b9589b-0ed9-40ed-b04b-04586b800769"
            }
          ]
        },
        {
          "id": "9f4a86a1-0f83-4daf-a6c8-f401d23ed374",
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
              "id": "b9379c3f-dc25-47d7-83f6-35745a7749d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateways",
      "item": [
        {
          "id": "72b3c95d-e6f2-4c19-8499-abbc6536f920",
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
              "id": "ec0d0c42-b3c8-4444-870b-7ebe79982fd4"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pair",
      "item": [
        {
          "id": "51d2496f-346f-4c45-bf46-4f0e44cae5bd",
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
              "id": "c8b26106-e741-4448-a4ef-960bb29ffbc9"
            }
          ]
        },
        {
          "id": "e6f9dc58-d652-487d-80d8-1f2ba37d1a4d",
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
              "id": "49d974df-c2d9-47e9-a832-13b1bda38173"
            }
          ]
        },
        {
          "id": "c8b7030a-9d22-4775-afcd-24596c86094d",
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
              "id": "ccb8b23c-bfff-4f48-a4c8-69f3d4cefd8f"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Paris",
      "item": [
        {
          "id": "752ac7c1-c494-47d5-8e8c-af3fc35a95c2",
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
              "id": "fcbb7957-6ff4-4da0-b81c-79d35f335969"
            }
          ]
        }
      ]
    },
    {
      "name": "NAT Gateways",
      "item": [
        {
          "id": "a31322e1-e1ea-4bb2-bb47-124c25590605",
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
              "id": "0b99ea91-daf9-4096-a62c-6a9ea609e25f"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC ACL",
      "item": [
        {
          "id": "24989ba3-784b-4d55-9c8b-85842dc9e990",
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
              "id": "f3fb1ac0-f11d-4c16-b3fc-10c5e098af71"
            }
          ]
        },
        {
          "id": "b6382140-04e3-49dc-981c-03c5f2ff7df9",
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
              "id": "a582f0e2-4b03-4b18-926f-bf1fffab7769"
            }
          ]
        }
      ]
    },
    {
      "name": "Network ACL",
      "item": [
        {
          "id": "1e9d67f9-99b8-4bdd-9942-96fdc584dcd0",
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
              "id": "29f2dbb0-a873-44dd-ba4a-7b45db469c36"
            }
          ]
        },
        {
          "id": "19a56f5c-2880-42e0-bf5f-f515c5d25591",
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
              "id": "0c7e0681-5b90-4db7-b67e-a05364061fc7"
            }
          ]
        },
        {
          "id": "8a70a59c-4a7b-4f2c-8b87-295dba104ad8",
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
              "id": "a700970d-57c3-448a-9a11-73ccf2cc4cea"
            }
          ]
        },
        {
          "id": "a321411f-dcd5-470c-9a6c-a44dd248bcc4",
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
              "id": "6af95aac-210c-43fa-ab25-a1aecb09147e"
            }
          ]
        },
        {
          "id": "bb542029-3c47-4c69-b4a2-20ac9724308f",
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
              "id": "6fbc73ac-636d-4136-8b41-29caa2e2adf0"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Group",
      "item": [
        {
          "id": "b491a35d-1e81-48ad-b09a-9eb92210f10c",
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
              "id": "56561ace-5054-4ffe-9ee9-30f1f0e503fb"
            }
          ]
        },
        {
          "id": "06f00106-4197-46a5-8809-179de16207d2",
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
              "id": "964c2730-c893-4662-b57b-07458bc40a2a"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Groups",
      "item": [
        {
          "id": "21256b7c-898f-4594-8b0e-626a4c0c73c1",
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
              "id": "331200c5-0ce7-454a-8062-7e065a4ba5e9"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Zones",
      "item": [
        {
          "id": "ac585b9c-917d-45ce-9b21-645c234273d6",
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
              "id": "0efca965-c274-4c59-aee2-242d3f2f30a1"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "c18570cf-2668-4c44-8afc-f41c53d7dac4",
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
              "id": "3d490a1e-8bf9-49ae-9d5c-3353fa172eb0"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instances",
      "item": [
        {
          "id": "fe3b7823-3156-4bfd-8eee-b5e97b10d35a",
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
              "id": "e72fac83-1e1b-44a6-926e-7b3e81119799"
            }
          ]
        },
        {
          "id": "444724aa-8b29-43da-aac0-195fe328d8b8",
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
              "id": "05dfb603-32ad-4ba2-bf99-7e5a3f732d3a"
            }
          ]
        },
        {
          "id": "dc5e9695-2d31-4db6-8f99-68353d2df7df",
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
              "id": "b86457fd-b3a1-46d5-a48e-4b4106b3e263"
            }
          ]
        },
        {
          "id": "99c2fb73-43a2-4ae1-9a37-92c25b807f29",
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
              "id": "188a45dc-c5e0-4a8e-aef6-de3b741f5fd7"
            }
          ]
        },
        {
          "id": "4aa55afd-aa0a-4950-826d-4e28938135fe",
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
              "id": "b05162ce-6668-4462-b8f5-4c34b249a88a"
            }
          ]
        },
        {
          "id": "e266b4ae-0cbd-4a30-9bb4-1b4633b30d8b",
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
              "id": "8bd180d3-334d-469c-bfa8-e1a93eb49ef7"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instance",
      "item": [
        {
          "id": "c62f6069-03d6-4205-86a0-c3e23a08abd6",
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
              "id": "7c0a5ba9-f1cd-4c68-aff0-502331d51934"
            }
          ]
        },
        {
          "id": "d0b2daac-aa76-4a12-bd4f-b0c612837834",
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
              "id": "725a29e6-a4f7-4980-b9c6-4a2b28addf0a"
            }
          ]
        },
        {
          "id": "8151726e-dc48-446b-84b0-2b59e38858cc",
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
              "id": "e0cb55dc-544c-48b5-8af4-4d68deceb301"
            }
          ]
        },
        {
          "id": "cf9341d3-595d-4f5e-be59-62f3791e6897",
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
              "id": "2494b9e2-bf96-4f5d-a70e-9f177282c9e4"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Format",
      "item": [
        {
          "id": "18454058-2653-46ff-bfc6-efc901aeaedf",
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
              "id": "579afc66-f2ab-4b8b-b7a8-b1effafb0080"
            }
          ]
        },
        {
          "id": "451b7722-39d9-4d36-9d80-e7edb5b249e9",
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
              "id": "9491b346-641d-4e34-a224-9ac1dea96479"
            }
          ]
        },
        {
          "id": "0f00af4b-636d-4dc4-b7fb-30eba61f8760",
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
              "id": "10a091db-176c-4f3f-b7fe-47e12a3926c4"
            }
          ]
        },
        {
          "id": "273c37f3-de5d-4128-a9b3-f56309513003",
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
              "id": "22024261-0456-4b35-a5f6-5f8f9ee4efea"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Table",
      "item": [
        {
          "id": "7f042588-e5aa-4109-bd0a-90f864f793c1",
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
              "id": "951d86f5-5866-4882-bf89-aeb2ee8bb862"
            }
          ]
        },
        {
          "id": "ec778352-382b-4140-b654-21dde3524b45",
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
              "id": "c60212a1-5fa1-4bd2-8563-3faa4efeadef"
            }
          ]
        },
        {
          "id": "63cc2afd-c906-4f7f-922d-39d1960d8387",
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
              "id": "ee4a0c72-9f75-47d5-8e04-a70732dbe0df"
            }
          ]
        },
        {
          "id": "5001d064-0d75-4fb2-b88a-c9f7cacc0613",
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
              "id": "c59f462f-8f40-4f44-92af-61b3b2c1047a"
            }
          ]
        },
        {
          "id": "ce097281-591d-45de-a4d2-47c11f01046b",
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
              "id": "1d7f5062-7776-4c84-87fa-e47f6fa78f1d"
            }
          ]
        },
        {
          "id": "81f439d3-45f7-4d0b-8019-8c8ea53b0b4a",
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
              "id": "878f48cf-5c18-4130-9bf5-66ba719cda40"
            }
          ]
        }
      ]
    },
    {
      "name": "Route",
      "item": [
        {
          "id": "f8b162a2-ef67-4f9e-b532-fd379e53a8c6",
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
              "id": "e92a6906-3a63-47a4-905c-4100f2a42c30"
            }
          ]
        },
        {
          "id": "717e482d-2ae3-4943-bde3-75b018bcdd36",
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
              "id": "59529514-7673-445a-87b0-28f87fbf0885"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "00b0117c-96b7-4e1e-99f1-42decb4f53ee",
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
              "id": "c25b2f8d-4222-4c49-aad9-23de8f115f72"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway",
      "item": [
        {
          "id": "1268cbaa-e997-42fb-bcc0-02cd7803bf4f",
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
              "id": "10536329-92ba-4b97-b035-7f942be9b493"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway Route Propogation",
      "item": [
        {
          "id": "c3038cf3-7f01-42b5-a36f-c3666a8a3ed9",
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
              "id": "a2dcf0a2-703b-46b4-b89c-a4a0376ac4c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Availability",
      "item": [
        {
          "id": "c93a8082-1f5d-450d-a9a2-f6303dccca8e",
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
              "id": "33f5cbfd-bd0f-4d6d-acd0-16e1c4f251c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Server Instances",
      "item": [
        {
          "id": "b323a95f-d148-4645-b98e-f4a9d5a0d766",
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
              "id": "3cbc96b9-5b2e-4862-8f2c-267d348aac4b"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instance",
      "item": [
        {
          "id": "85c250d9-faa9-435a-8039-8a3e4c62d9f7",
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
              "id": "6a955bc8-1b67-4049-9e4d-66a50089b22c"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instances",
      "item": [
        {
          "id": "d6bef67b-ce7d-41e0-bfbd-6331688edc6d",
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
              "id": "e83ec020-1e02-46bb-b691-d6e086b69be3"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Group",
      "item": [
        {
          "id": "70938056-640c-430e-b2ba-d34469665a91",
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
              "id": "48b8039b-1fb3-4bae-b916-ddcf629bed67"
            }
          ]
        },
        {
          "id": "003b9cca-922a-4a9d-a265-a44f2efc76b7",
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
              "id": "af65da12-dcc4-4166-b0a1-388d43ca3bd3"
            }
          ]
        },
        {
          "id": "6287ddfc-8a89-4695-85cc-6151203ac03f",
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
              "id": "a6174f54-dd34-4228-8674-84f6692fa3bb"
            }
          ]
        },
        {
          "id": "9489ffac-c756-4bfa-bc56-faf622723fe8",
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
              "id": "235d7348-e24f-4504-a036-5bc3478f6155"
            }
          ]
        },
        {
          "id": "15916c25-0477-4b26-b435-5f330be51a9b",
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
              "id": "28093688-2ae0-4771-b491-d9e81679bac4"
            }
          ]
        }
      ]
    },
    {
      "name": "Security  Group",
      "item": [
        {
          "id": "59e87872-4e29-4088-85ae-eaf2c3f1be0e",
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
              "id": "b7317bf5-b6fd-48e5-bdd8-cfec68c672c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Groups",
      "item": [
        {
          "id": "28b0a95c-2477-4b2f-a2a2-7b4c6caf7408",
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
              "id": "a5eb3b80-4fc1-49de-a689-43177569035c"
            }
          ]
        },
        {
          "id": "cd822bc7-a590-4734-8d62-1cef2ed0bf23",
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
              "id": "dbcdf884-bda1-4748-ac1f-45a74fa1b598"
            }
          ]
        },
        {
          "id": "c126e3c5-8538-45c5-9ba0-8aa0fec1aea5",
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
              "id": "908c84a0-f015-41f5-a58f-124b839b7f8f"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance",
      "item": [
        {
          "id": "83eb61c0-d2dc-4d1d-b31f-4196ebceffe0",
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
              "id": "c10bf319-b369-462d-bcde-84a930afe8bb"
            }
          ]
        },
        {
          "id": "6f0e27cd-eb43-4daa-9815-55d5c2d73769",
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
              "id": "bd680342-e533-4ce4-8b47-9669327bc3f7"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnet",
      "item": [
        {
          "id": "b25cb1c3-4d7b-4e06-90ef-d02e1fa82310",
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
              "id": "2374598c-df34-4f0b-9caa-375872e74d8f"
            }
          ]
        },
        {
          "id": "b1add901-55dd-44b6-93b7-75eeec8fbbbe",
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
              "id": "7060baae-38ce-40e4-833a-aaf48c20aeb1"
            }
          ]
        },
        {
          "id": "4d6a4084-bc6d-4835-ab08-d74b2326bfec",
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
              "id": "bdb34ef2-4951-4cc8-84ad-c2e74bc9a7d7"
            }
          ]
        },
        {
          "id": "975b8fb8-11da-48fa-9ad6-3fc3e7e1a855",
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
              "id": "3083c8f7-727d-4317-b9d7-07e501d878ea"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed Subscription",
      "item": [
        {
          "id": "bfdb825b-d49d-450e-86b2-f9148652c2cd",
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
              "id": "921ce317-e429-47e6-b8f7-a36df043c17a"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed",
      "item": [
        {
          "id": "0e2f680e-2068-47ec-96e9-ea791a57f159",
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
              "id": "bb8aa9a8-8d08-468f-bbe2-95347c2a2a99"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "0faa7ac6-ddfb-472e-bd0f-cd861c4d06fa",
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
              "id": "d7039539-96d7-48d9-b3e0-97238ee84f4e"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Price History",
      "item": [
        {
          "id": "392e84d7-e018-4f07-b6f6-c69a75db3ca3",
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
              "id": "accf831e-ecaa-4bf6-a896-16b5a098a192"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet",
      "item": [
        {
          "id": "785b79e8-fc6b-46a6-bb55-f13c36c1ab25",
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
              "id": "6a44a729-f782-42bc-abed-a2d9955c5c02"
            }
          ]
        },
        {
          "id": "6fa38628-cced-4719-ae51-e1bc76a3d05f",
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
              "id": "11aed0f5-7734-4157-871a-1cd4f528b51e"
            }
          ]
        },
        {
          "id": "88fb051a-e809-4cf2-83c7-de682b083300",
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
              "id": "7519b920-878b-404e-b167-462087197acf"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Instance",
      "item": [
        {
          "id": "e514ff2a-3bbb-401d-89f4-cf1a0561c7c5",
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
              "id": "50bdd457-0a71-4277-990a-c1f0da4d72b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Request History",
      "item": [
        {
          "id": "a7451b23-6f47-4726-a1f7-723c0c307c69",
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
              "id": "da9a6526-33d3-407b-b49c-697820e6599e"
            }
          ]
        }
      ]
    },
    {
      "name": "Sport Fleet Requests",
      "item": [
        {
          "id": "847b550f-e933-4da6-bca0-22c4ac6227b2",
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
              "id": "041cc4f7-7bad-4d7a-a0a3-af182e3ed5c5"
            }
          ]
        }
      ]
    },
    {
      "name": "CIDR Block",
      "item": [
        {
          "id": "837cb3ba-58ab-461f-ad5d-8540b2177ed5",
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
              "id": "f73d18a0-26ee-4a69-aebd-6d2bd9caba74"
            }
          ]
        },
        {
          "id": "64ae09c4-a6f0-49f8-99bb-d01f9807d9e0",
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
              "id": "8cb5fa3a-9512-4aa8-b98b-1a38951ee96d"
            }
          ]
        },
        {
          "id": "fe8f1ead-bd18-4fb5-b4c2-ee0a47da5eee",
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
              "id": "145a182a-bbbc-4590-a637-26b6c8ec1367"
            }
          ]
        },
        {
          "id": "22d94be8-a373-4a07-ae8a-48942b0f1c79",
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
              "id": "9af5ca68-5069-4820-8da7-4461e5ef47c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnets",
      "item": [
        {
          "id": "3552aec7-77c4-42d6-8ae1-339cb4def8fd",
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
              "id": "d94eff05-8a1c-4d39-a90c-d7ff857d976e"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "f4f3ab55-59c2-46a5-b207-19193f5bc83c",
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
              "id": "4170b650-4676-41ab-ab6b-eb25cfc363e9"
            }
          ]
        },
        {
          "id": "fbe9bc73-488c-45e7-b5ab-7adff844c55f",
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
              "id": "5d8b13a2-bca9-48bf-bc88-c1fbe65c8b4f"
            }
          ]
        },
        {
          "id": "b91c410d-89aa-4ee3-b80f-2a7c4bed1b29",
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
              "id": "ff75c831-f2c2-482f-bd30-4e3bb7b6e494"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Task",
      "item": [
        {
          "id": "6d8cf1d8-c992-440f-8736-f16205d08041",
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
              "id": "a6ff3a92-8e85-4722-9a9f-b0b4a85737c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Version Tasks",
      "item": [
        {
          "id": "f691357c-ff03-4a52-af2e-0beca2a4c910",
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
              "id": "ef84c581-c9e0-4fff-a585-997ceb5a3491"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image Tasks",
      "item": [
        {
          "id": "d9108d1f-20d4-42f4-95f5-a34abe260609",
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
              "id": "bfcbd558-9470-436b-a5ab-262c27e2929d"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Snapshot Takss",
      "item": [
        {
          "id": "9a77e181-1439-42cb-82e8-a94145f98dc6",
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
              "id": "7d004804-04c3-403b-84ce-39cffe059c80"
            }
          ]
        }
      ]
    },
    {
      "name": "Import Image",
      "item": [
        {
          "id": "847c7129-839f-43bd-9c9e-e68c0aa99b7b",
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
              "id": "bfd13a27-a364-482a-81c4-f7f353ef3f16"
            }
          ]
        }
      ]
    },
    {
      "name": "Export Task",
      "item": [
        {
          "id": "af71efcf-515f-417b-882f-20f711dded00",
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
              "id": "acf12208-0d20-4ae0-bb3a-429522237375"
            }
          ]
        },
        {
          "id": "e94ee552-747a-46c9-ac76-647178ea3b72",
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
              "id": "f93b35bb-2b6b-43f7-906a-92cf40473249"
            }
          ]
        }
      ]
    },
    {
      "name": "Export Takss",
      "item": [
        {
          "id": "8d9f0ce4-cbfb-4d7b-a9b9-e6fa6f1e4423",
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
              "id": "a20f7dfe-7234-47ea-8e09-65bbedf27477"
            }
          ]
        }
      ]
    }
  ]
}