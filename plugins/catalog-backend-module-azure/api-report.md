## API Report File for "@backstage/plugin-catalog-backend-module-azure"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { CatalogProcessor } from '@backstage/plugin-catalog-backend';
import { CatalogProcessorEmit } from '@backstage/plugin-catalog-backend';
import { Config } from '@backstage/config';
import { LocationSpec } from '@backstage/plugin-catalog-backend';
import { Logger } from 'winston';
import { ScmIntegrationRegistry } from '@backstage/integration';

// @public
export class AzureDevOpsDiscoveryProcessor implements CatalogProcessor {
  constructor(options: {
    integrations: ScmIntegrationRegistry;
    logger: Logger;
  });
  // (undocumented)
  static fromConfig(
    config: Config,
    options: {
      logger: Logger;
    },
  ): AzureDevOpsDiscoveryProcessor;
  // (undocumented)
  getProcessorName(): string;
  // (undocumented)
  readLocation(
    location: LocationSpec,
    _optional: boolean,
    emit: CatalogProcessorEmit,
  ): Promise<boolean>;
}
```
