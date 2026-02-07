# IPFS Storage

| Field | Value |
|-------|-------|
| Type | `ipfs-storage` |
| ID | `6639bff9` |
| Category | app |
| Tags | ipfs, storage, pinata, decentralized, metadata |
| Description | Decentralized storage (Pinata/Web3.Storage) |

## Configuration

| Setting | Value |
|---------|-------|
| Provider | pinata |
| Generate Metadata Schemas | Enabled |
| Generate U I | Enabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `PINATA_JWT` | Pinata JWT token | Yes | Yes |  |
| `NEXT_PUBLIC_PINATA_GATEWAY` | Pinata gateway URL | No | No | https://gateway.pinata.cloud |

## Documentation

### IPFS Storage

# IPFS Storage

Decentralized file storage using Pinata.

## Usage

```typescript
import { useIPFS } from '@/hooks/useIPFS';

function UploadForm() {
  const { upload, isUploading } = useIPFS();
  
  const handleUpload = async (file: File) => {
    const { cid, url } = await upload(file);
    console.log('Uploaded:', url);
  };
}
```


## File Structure

This component would generate the following files:

- `storage-client.ts` (frontend-lib)
- `useIPFS.ts` (frontend-hooks)
- `FileUpload.tsx` (frontend-components)

## Integration Points

**Depends on:**
- Erc721-stylus (`c8f520e5`)
- Erc1155-stylus (`2f3fff28`)

